<script setup>
import { deals } from '@/data/promoData.js'
</script>

<template>
  <div class="py-12 flex items-center justify-between ">
    <h2 class="text-2xl font-bold">Up to -40%  Order.uk exclusive deals</h2>
    <div >
      <ul class="flex text-xl items-center gap-6">
        <li class="" >
            <router-link active-class="border border-orange-400 py-2 px-8 text-orange-400" class=" hover:border border2-orange-400 py-2 px-8 rounded-full hover:text-orange-400" to="/">Vegan</router-link>
          </li>
          <li >
            <router-link class=" hover:border border-orange-400  py-2 px-8 rounded-full hover:text-orange-400" to="">Sushi</router-link>
          </li>
          <li >
            <router-link class="hover:border border-orange-400 py-2 px-8 rounded-full hover:text-orange-400" to="">Pizza & Fast food</router-link>
          </li>
          <li >
            <router-link class="hover:border border-orange-400 py-2 px-8 rounded-full hover:text-orange-400" to="">Others</router-link>
          </li>
      </ul>
    </div>
  </div>
  <div class="flex justify-between">
    <div v-for="deal in deals" :key="deal.id">
      <div class="relative">
        <div class="flex items-center justify-end">
        <span class="flex items-center justify-center w-[5.5rem] h-16 bg-black/90 text-white font-semibold rounded-b-2xl absolute top-0 right-5">{{ deal.discount }}%</span>
      </div>
        <img :src="deal.img" alt="" />
        <div class="absolute z-10 top-[14rem] ml-12">
          <p class="text-orange-400 font-medium text-lg">Restaurant</p>
          <p class="text-white text-[1.5rem] font-bold">{{ deal.name }}</p>
        </div>
      </div>
    </div>
  </div>
</template>
