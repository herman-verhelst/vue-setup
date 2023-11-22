<script setup>
import Nav from "@/components/Nav.vue";
</script>

<template>

  <!-- Button om drawer te tonen, button kan in elk bestand geplaatst worden. -->
  <button aria-controls="navLeft"
          class="button"
          data-drawer-show="navLeft"
          data-drawer-target="navLeft"
          type="button">
    Show drawer from the left
  </button>

  <!-- drawer die verschijnt, hij komt nu van links het scherm binnen -->
  <div id="navLeft"
       aria-labelledby="drawer-label"
       class="drawer drawer--left -translate-x-full"
       tabindex="-1">
    <Nav drawer-id="navLeft"></Nav>
  </div>

</template>

<style scoped>

</style>