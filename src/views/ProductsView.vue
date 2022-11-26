<script setup>
import ProductsItem from "../components/ProductsItem.vue";
</script>

<template>
  <div class="productsWrapper">
    <ProductsItem />
  </div>
</template>

<style scoped>
.productsWrapper {
  overflow-y: auto;
}
</style>
