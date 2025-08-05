<script setup>
import { ref } from 'vue'

const count = ref(0)

function increment() {
  count.value++
}
</script>

<style scoped>
button {
  padding: 12px 12px;
  font-size: 16px;
  cursor: pointer;
  background-color: #181818;
  color: rgb(235, 235, 235, 0.64);
  border: none;
  border-radius: 5px;
}
</style>

<template>
  <button @click="increment">{{ count }}</button>
</template>
