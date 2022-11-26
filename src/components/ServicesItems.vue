<template>
  <div class="productsList">
    <h1 class="productItem">Service 1</h1>
    <h1 class="productItem">Service 2</h1>
    <h1 class="productItem">Service 3</h1>
    <h1 class="productItem">Service 4</h1>
    <h1 class="productItem">Service 5</h1>
  </div>
</template>

<script>
export default {
  name: "ServicesItems.vue",
};
</script>

<style scoped>
.productsList {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.productItem {
  color: #2c3e50;
}
</style>
