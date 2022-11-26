<template>
  <div class="serviceList">
    <h1 class="servicetItem">Service 1</h1>
    <h1 class="servicetItem">Service 2</h1>
    <h1 class="servicetItem">Service 3</h1>
    <h1 class="servicetItem">Service 4</h1>
    <h1 class="servicetItem">Service 5</h1>
  </div>
</template>

<script>
export default {
  name: "ServicesItems.vue",
};
</script>

<style scoped>
.serviceList {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.servicetItem {
  color: #2c3e50;
}
</style>
