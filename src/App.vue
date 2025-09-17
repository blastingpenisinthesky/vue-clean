<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <nav class="bg-gray-950 text-white p-4 space-x-4">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav>
  <main>
    <RouterView />
  </main>
</template>

<style scoped></style>
