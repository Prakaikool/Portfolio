<script setup>
import { RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue'
</script>

<template>
  <div>
    <NavBar :page="currentPage" />
    <RouterView />
  </div>
</template>

<style scoped></style>
