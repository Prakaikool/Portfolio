<script setup>
import { RouterLink } from 'vue-router'
import { ref } from 'vue'

const menuOpen = ref(false)
const toggleMenu = () => {
  menuOpen.value = !menuOpen.value
}
</script>

<template>
  <nav class="navbar">
    <div class="logo">Prakaikool Teepraken</div>

    <div class="hambuger" @click="toggleMenu">
      <span :class="{ open: menuOpen }"></span>
      <span :class="{ open: menuOpen }"></span>
      <span :class="{ open: menuOpen }"></span>
    </div>

    <div class="nav-links" :class="{ active: menuOpen }">
      <router-link class="link" to="/" active-class="isActive">Home</router-link>
      <router-link class="link" to="/projects" active-class="isActive">Projects</router-link>
      <router-link class="link" to="/contact" active-class="isActive">Contact</router-link>
    </div>
  </nav>
</template>

<style scoped></style>
