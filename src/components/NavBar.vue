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

<style scoped>
.navbar {
  font-size: 24px;
  font-family: 'Archivo Black', sans-serif;
  background-color: #f6f6ef;
  color: black;
  padding: 5px 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1000;
  box-shadow: 0 2px 8px hsl(0, 0%, 0%);
  width: 100%;
}

.link {
  text-decoration: none;
  color: black;
}

.nav-links {
  display: flex;
  gap: 30px;
  align-items: center;
}
</style>
