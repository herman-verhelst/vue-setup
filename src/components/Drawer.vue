<script setup>
import Nav from "@/components/Nav.vue";
</script>

<template>

  <!-- Button om drawer te tonen, button kan in elk bestand geplaatst worden. -->
  <button aria-controls="nav"
          class="button"
          data-drawer-show="nav"
          data-drawer-target="nav"
          type="button">
    Show drawer
  </button>

  <!-- drawer die verschijnt, hij komt nu van links het scherm binnen -->
  <div id="nav"
       aria-labelledby="drawer-label"
       class="drawer -translate-x-full"
       tabindex="-1">
    <Nav></Nav>
  </div>

</template>

<style scoped>

</style>