<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Textbox from "./components/Textbox.vue";
import Imgbox from "./components/Imgbox.vue";
</script>

<template>
  <header>
    <h1 class="title-header">Nuestra Historia</h1>
  </header>
  <main>
    <div class="grid-container">
      <Textbox />
      <Imgbox />
    </div>
  </main>
</template>

<style lang="postcss" scoped>
header {
  text-align: center;
  border-style: solid none solid none;
  border-width: 1px;
  margin: 30px;
  .title-header {
    font-style: italic;
    padding: 10px;
  }
}

main {
  .grid-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-column-gap: 10px;
    grid-row-gap: 10px;
    align-items: center;
    justify-items: center;
  }
}
</style>
