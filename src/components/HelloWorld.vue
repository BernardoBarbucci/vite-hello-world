<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>La mia prima app con Vite!</h1>
  <p>utilizzando Vue!</p>
</template>

<style scoped>
h1 {
  transition: transform 0.5s ease-in-out;
}

h1:hover {
  transform: scale(1.2);
  color: rgb(166 87 246);
}


p {
  margin-top: 2rem;
  font-size: 10px;
  transition: transform 0.5s ease-in-out;
}

p:hover {
  transform: rotate(360deg);
}
</style>
