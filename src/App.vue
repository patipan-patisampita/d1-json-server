<script setup>
import { RouterView } from 'vue-router';
import NavBar from './views/layouts/NavBar.vue'
import FooterView from './views/layouts/FooterView.vue';
</script>

<template>
  <NavBar />
  <RouterView />
  <FooterView />
</template>

<style scoped>
</style>
