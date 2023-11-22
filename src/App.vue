<script setup>
import { RouterView } from 'vue-router'
import Nav from "@/components/Nav.vue";
import Drawer from "@/components/Drawer.vue";
</script>

<template>
  <Drawer></Drawer>
  <RouterView />
</template>

<style scoped>
</style>
