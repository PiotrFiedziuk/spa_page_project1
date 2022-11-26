<template>
  <div class="serviceList">
    <h1 class="serviceItem">Product 1</h1>
    <h1 class="serviceItem">Product 2</h1>
    <h1 class="serviceItem">Product 3</h1>
    <h1 class="serviceItem">Product 4</h1>
    <h1 class="serviceItem">Product 5</h1>
    <h1 class="serviceItem">Product 6</h1>
  </div>
</template>
<script>
export default {
  name: "ProductsItem.vue",
};
</script>

<style scoped>
.serviceList {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.serviceItem {
  color: #2c3e50;
}
</style>
