<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <div>
    <div>
      <!-- LOGO -->
      <div>
        <img src="../assets/icons/LOGO 2.png" alt="logo" />
        <img src="../assets/images/app-store-badges-en 1.png" alt="badges" />
        <p>Company # 490039-445, Registered with<br />House of companies.</p>
      </div>

      <!-- SUBSCRIBE -->
      <div>
        <h4>Get Exclusive Deals in your Inbox</h4>
        <!-- SEARCH -->
        <div class="mt-12">
          <p class="text-white py-2 pl-5">Enter a postcode to see what we deliver</p>
          <div class="flex bg-gray-200 w-[23rem] rounded-full">
            <input
              type="text"
              placeholder="youremail@gmail.com"
              class="rounded-full bg-gray-200 outline-none text-gray-600 px-6"
            />
            <button class="bg-orange-400 py-4 px-20 text-white rounded-full">Subscribe</button>
            <p>we wont spam, read our email policy</p>
            <div>
              <img src="../assets/icons/kfc" alt="" />
            </div>
          </div>
        </div>
      </div>
      <div></div>
    </div>
    <div class="bg-black/90 text-white">
      <p>Order.uk Copyright 2024, All Rights Reserved.</p>
      <ul>
        <li>
          <router-link>Privacy Policy</router-link>
        </li>
        <li>
          <router-link>Terms</router-link>
        </li>
        <li>
          <router-link>Pricing</router-link>
        </li>
        <li>Do not sell or share my personal information</li>
      </ul>
    </div>
  </div>
</template>
