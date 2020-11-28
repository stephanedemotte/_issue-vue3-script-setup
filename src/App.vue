<template>
  <div>{{ isActive.value }}(work in build)</div>
  <div>{{ isActive }}(work in dev)</div>
  <button @click="isActive.value = !isActive.value">change value</button>
  <HelloWorld />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import { isActive } from './components/HelloWorld.vue'
</script>
