<script setup>
import { RouterView } from 'vue-router'
import PromoNav from './components/PromoNav.vue';
import NavBar from './components/NavBar.vue';
</script>

<template>
  <div class="w-[79vw] mx-auto">
  <PromoNav />
  <NavBar />

  <RouterView />
</div>
</template>

