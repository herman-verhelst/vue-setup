<script setup>
import Nav from "@/components/Nav.vue";
</script>

<template>

  <!-- Button om drawer te tonen, button kan in elk bestand geplaatst worden. -->
  <button aria-controls="navTop"
          class="button"
          data-drawer-placement="top"
          data-drawer-show="navTop"
          data-drawer-target="navTop"
          type="button">
    Show drawer from the top
  </button>

  <!-- drawer die verschijnt, hij komt nu van rechts het scherm binnen -->
  <div id="navTop"
       aria-labelledby="drawer-label"
       class="drawer drawer--top -translate-y-full"
       tabindex="-1">
    <Nav drawer-id="navTop"></Nav>
  </div>

</template>

<style scoped>

</style>