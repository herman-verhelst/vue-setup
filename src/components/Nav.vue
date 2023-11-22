<script setup>
const props = defineProps(['drawerId'])
</script>

<template>
<nav>
  <ul>
    <li :data-drawer-hide="drawerId"><router-link to="/">Link to home</router-link></li>
    <li :data-drawer-hide="drawerId"><router-link to="/about">Link to about</router-link></li>
  </ul>
</nav>
</template>

<style scoped>

</style>