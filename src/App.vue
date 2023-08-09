<script setup>
import { RouterView } from 'vue-router';
import NavBar from './components/NavBar.vue';
</script>

<template>
  <main>
    <NavBar />
    <RouterView />  
  </main>
  
</template>

<style lang="scss">

body {
  background-color: rgb(243, 243, 243);
  margin: 0;
  padding: 0;
  border: 0;
}
</style>
