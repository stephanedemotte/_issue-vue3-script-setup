<template>
  <div>
    HelloWorld [{{ isActiveTpl }}]
  </div>
</template>

<script>
import { ref } from 'vue'
export const isActive = ref(false)
</script>

<script setup>
const isActiveTpl = isActive
</script>
