<script setup>
import HomeHero from '@/components/HomeHero.vue'
import PromoDeals from '@/components/PromoDeals.vue';
import Category from '@/components/Category.vue';
import PopularRes from '@/components/PopularRes.vue';
import DownloadApp from '@/components/DownloadApp.vue';
import HomeGetstarted from '@/components/HomeGetstarted.vue';
import KnowMore from '@/components/KnowMore.vue';
import OrderSatats from '@/components/OrderSatats.vue';
</script>

<template>
  <div class="pt-[9.5rem]">
    <header>
      <HomeHero />
    </header>
    <main>
      <PromoDeals />
      <Category />
      <PopularRes />
      <DownloadApp />
      <HomeGetstarted />
      <KnowMore />
      <OrderSatats />
    </main>
  </div>
</template>
