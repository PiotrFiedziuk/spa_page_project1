<template>
  <div class="productsList">
    <div class="productItem">
      <h1>Product 1</h1>
      <div>Description about product 1</div>
    </div>
    <div class="productItem">
      <h1>Product 2</h1>
      <div>Description about product 2</div>
    </div>
    <div class="productItem">
      <h1>Product 3</h1>
      <div>Description about product 3</div>
    </div>
    <div class="productItem">
      <h1>Product 4</h1>
      <div>Description about product 4</div>
    </div>
    <div class="productItem">
      <h1>Product 5</h1>
      <div>Description about product 5</div>
    </div>
    <div class="productItem">
      <h1>Product 6</h1>
      <div>Description about product 6</div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ProductsItem.vue",
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
