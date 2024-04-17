<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
    <RouterLink to="/profile">Profile</RouterLink>
  </nav>

  <main class="main-content">
    <RouterView />
  </main>

  <footer>footer stuff</footer>
</template>

<style scoped>
nav {
  display: flex;
  gap: 10px;
  justify-content: center;
}

.main-content {
  flex-grow: 1;
  display: flex;
  justify-content: center;
}
</style>
