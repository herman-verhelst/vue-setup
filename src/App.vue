<script setup>
import { RouterView } from 'vue-router'
import DrawerLeft from "@/components/DrawerLeft.vue";
import DrawerRight from "@/components/DrawerRight.vue";
import DrawerTop from "@/components/DrawerTop.vue";
</script>

<template>
  <DrawerLeft></DrawerLeft>
  <DrawerRight></DrawerRight>
  <DrawerTop></DrawerTop>
  <RouterView />
</template>

<style scoped>
</style>
