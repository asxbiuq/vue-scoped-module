<template>
  <h1>vue css module</h1>
  <div :class="$style.wrapper">
    <p>parent</p>
    <ModuleChild />
  </div>
</template>

<script setup>
  import ModuleChild from './ModuleChild.vue'
</script>
<style module>
  .wrapper {
    outline: 2px solid blue;
  }
</style>
