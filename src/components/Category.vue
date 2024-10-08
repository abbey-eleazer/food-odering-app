<script setup>
import { categories } from '@/data/promoData';

</script>

<template>
  <div class="py-12 text-2xl font-bold">
    <h2>Order.uk Popular Categories</h2>
  </div>
  <div class="flex justify-between">
    <div v-for="category in categories" :key="category.id">
      <img :src="category.img" alt="food">
      <div class="bg-black/90 text-white pl-4 py-2 rounded-b-2xl">
        <p class="font-semibold text-orange-400 text-lg">{{ category.name }}</p>
        <p>{{ category.numRestaurant }}</p>
      </div>
    </div>
  </div>
</template>