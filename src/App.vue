<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Textbox from './components/Textbox.vue';
</script>

<template>
  <header>
    <h1 class="title-header">Nuestra Historia</h1>
  </header>
  <Textbox />
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
</style>
