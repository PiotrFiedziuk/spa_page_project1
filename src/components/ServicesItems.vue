<template>
  <div class="serviceList">
    <div class="serviceItem">
      <h1>Service 1</h1>
      <div>Description about service 1</div>
    </div>
    <div class="serviceItem">
      <h1>Service 2</h1>
      <div>Description about service 1</div>
    </div>
    <div class="serviceItem">
      <h1>Service 3</h1>
      <div>Description about service 1</div>
    </div>
    <div class="serviceItem">
      <h1>Service 4</h1>
      <div>Description about service 1</div>
    </div>
    <div class="serviceItem">
      <h1>Service 5</h1>
      <div>Description about service 1</div>
    </div>
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

.serviceItem {
  color: #2c3e50;
}
</style>
