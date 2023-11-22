<script setup>
import Nav from "@/components/Nav.vue";
</script>

<template>

  <!-- Button om drawer te tonen, button kan in elk bestand geplaatst worden. -->
  <button aria-controls="navRight"
          class="button"
          data-drawer-placement="right"
          data-drawer-show="navRight"
          data-drawer-target="navRight"
          type="button">
    Show drawer from the right
  </button>

  <!-- drawer die verschijnt, hij komt nu van rechts het scherm binnen -->
  <div id="navRight"
       aria-labelledby="drawer-label"
       class="drawer drawer--right translate-x-full"
       tabindex="-1">
    <Nav drawer-id="navRight"></Nav>
  </div>

</template>

<style scoped>

</style>