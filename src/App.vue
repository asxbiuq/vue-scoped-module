<template>
  <div :class="$style.wrapper">
    <p>parent</p>
    <Child />
  </div>
</template>

<script setup>
  import Child from './components/Child.vue'
</script>
<style module>
  .wrapper {
    outline: 2px solid blue;
  }
</style>
