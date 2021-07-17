<template>
  <div class="app">
    <MeatLogo />
    <MultilevelMenu />
  </div>
</template>

<script setup>
import MeatLogo from './components/MeatLogo.vue';
import MultilevelMenu from './components/MultilevelMenu.vue';
</script>

<style>
body {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  letter-spacing: 1px;
  margin: 0;
  padding: 0;
}

.app {
  background-color: #222;
  min-height: 100vh;
  padding: 5rem 10rem;
  text-align: center;
}
</style>
