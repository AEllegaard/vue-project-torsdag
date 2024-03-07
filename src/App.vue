<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>

  <nav class="flex justify-evenly text-6xl">
    <RouterLink class="hover:text-blue-700" to="/home">Home</RouterLink>
    <RouterLink class="hover:text-blue-700" to="/about">About</RouterLink>
    <RouterLink class="hover:text-blue-700" to="/projects">Projects</RouterLink>
  </nav>

  <RouterView/>
</template>

<style scoped>

</style>
