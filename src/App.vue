<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>

  <nav class="flex justify-evenly text-6xl">
    <RouterLink to="/home">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
    <RouterLink to="/projects">Projects</RouterLink>
  </nav>

  <RouterView/>

</template>

<style scoped>

</style>
