<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="menuWrapper">
    <div>Logo</div>
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
  height: 50px;
  display: flex;
  background-color: lightslategray;
}

.menu {
  height: 100%;
  display: flex;
  justify-content: flex-start;
  gap: 8px;
}
.menuItem {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
}
.menuItem:hover {
  color: blue;
  background-color: lightgray;
}
.content {
  padding: 0 12px;
}
</style>
