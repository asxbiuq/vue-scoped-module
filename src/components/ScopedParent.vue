<template>
  <h1>vue css scoped</h1>
  <div class="wrapper">
    <p>parent</p>
    <ScopedChild />
  </div>
</template>

<script setup>
  import ScopedChild from './ScopedChild.vue'
</script>
<style scoped>
  .wrapper {
    outline: 2px solid blue;
  }
</style>
