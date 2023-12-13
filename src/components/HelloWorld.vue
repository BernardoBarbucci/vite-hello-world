<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>La mia prima app con Vite!</h1>
  <p><i class="fa-brands fa-galactic-republic"></i></p>
</template>

<style scoped>
h1 {
  transition: transform 1s ease-in-out;
  filter: drop-shadow(0 0 2em #646cffaa);
  color: #c2c5ffaa;
  will-change: filter;
  /* transition: filter 500ms; */

}

h1:hover {
  transform: scale(1.2);
  color: rgb(166 87 246);
  filter: drop-shadow(0 0 2em rgb(166 87 246));
}


p {
  margin-top: 2rem;
  font-size: 2rem;
  transition: transform 0.5s ease-in-out;
}

p:hover {
  transform: rotate(360deg);
}
</style>
