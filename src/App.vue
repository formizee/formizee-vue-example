<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Header />
  <main>
    <RouterView />
  </main>
  <Footer />
</template>

<style>
  #app {
    display: flex;
    align-items: center;
    flex-direction: column;
  }

  main {
    width: 100%;
    flex-grow: 1;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
</style>
