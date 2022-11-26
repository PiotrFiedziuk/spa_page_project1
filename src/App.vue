<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="menuWrapper">
    <nav class="menu">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
      <RouterLink to="/contact">Contact</RouterLink>
      <RouterLink to="/products">Products</RouterLink>
      <RouterLink to="/services">Services</RouterLink>
    </nav>
  </div>
  <div>
    <RouterView />
  </div>
</template>

<style scoped>
.menuWrapper {
  width: 100%;
  display: flex;
  height: 50px;
  justify-content: center;
  align-items: center;
}

.menu {
  display: flex;
  justify-content: space-evenly;
  gap: 8px;
}
</style>
