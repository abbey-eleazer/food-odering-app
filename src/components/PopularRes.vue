<script setup>
import { restaurants } from '@/data/promoData';
</script>

<template>
  <div class="py-12 text-2xl font-bold">
    <h2>Popular Restaurants </h2>
  </div>
  <div class="flex justify-between">
    <div v-for="restaurant in restaurants" :key="restaurant.id">
      <img :src="restaurant.img" alt="food">
      <div class="bg-orange-400 text-white py-3 rounded-b-2xl">
        <p class="font-semibold text-white text-lg text-center">{{ restaurant.name }}</p>
      </div>
    </div>
  </div>
</template>