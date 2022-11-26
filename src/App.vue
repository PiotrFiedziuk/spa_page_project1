<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="menuWrapper">
    <nav class="menu">
      <RouterLink class="menuItem" to="/">Home</RouterLink>
      <RouterLink class="menuItem" to="/about">About</RouterLink>
      <RouterLink class="menuItem" to="/contact">Contact</RouterLink>
      <RouterLink class="menuItem" to="/products">Products</RouterLink>
      <RouterLink class="menuItem" to="/services">Services</RouterLink>
    </nav>
  </div>
  <div class="content">
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
  background-color: lightgray;
}

.menu {
  width: 100%;
  display: flex;
  justify-content: space-evenly;
  gap: 8px;
}
.menuItem:hover {
  color: blue;
}
.content {
  padding: 0 12px;
}
</style>
