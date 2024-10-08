<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="bg-[#D9D9D9] mt-32 ">
    <div class="w-[79vw] h-[23rem] mx-auto flex items-center justify-between">
      <!-- LOGO -->
      <div>
        <img src="../assets/icons/LOGO 2.png" alt="logo" />
        <img  class="py-8" src="../assets/images/app-store-badges-en 1.png" alt="badges" />
        <p>Company # 490039-445, Registered with<br />House of companies.</p>
      </div>

      <!-- SUBSCRIBE -->
      <div>
        <h4 class="text-xl font-bold pb-8">Get Exclusive Deals in your Inbox</h4>
        <!-- SEARCH -->
        <div class="mt-2">
          
          <div class="flex bg-gray-200 w-[23rem] rounded-full">
            <input
              type="text"
              placeholder="youremail@gmail.com"
              class="rounded-full bg-gray-200 outline-none text-gray-600 px-6"
            />
            <button class="bg-orange-400 py-4 px-20 text-white rounded-full">Subscribe</button>
          </div>
          <p class="pt-4 pl-5">we wont spam, read our email policy</p>
          <div class="flex gap-4 pt-6 pl-6">
            <router-link>
              <img src="../assets/icons/Facebook.png" alt="facebook" />
            </router-link>
            <router-link>
              <img src="../assets/icons/Instagram.png" alt="instagram" />
            </router-link>
            <router-link>
              <img src="../assets/icons/TikTok.png" alt="tiktok" />
            </router-link>
            <router-link>
              <img src="../assets/icons/Snapchat.png" alt="snapchat" />
            </router-link>
          </div>
        </div>
      </div>


      <!-- LINKS -->
      <div class="flex items-center gap-12">
        <div>
          <ul class="flex flex-col gap-5">
            <li class="text-lg font-bold">Legal Pages</li>
            <li>Terms and conditions</li>
            <li>Privacy</li>
            <li>Cookies</li>
            <li>Modern Slavery Statement</li>
          </ul>
        </div>
        <div>
          <ul class="flex flex-col gap-5 ">
            <li class="text-lg font-bold">Important Links</li>
            <li>Get help</li>
            <li>Add your restaurant</li>
            <li>Sign up to deliver</li>
            <li>Create a business account</li>
          </ul>
        </div>
      </div>
    </div>
    <img src="https://src/assets/images/restaurant 1.png" alt="">

     <!-- COPYRIGHT -->
    <div class="bg-black/90 text-white ">
      <div class="w-[79vw] mx-auto flex items-center justify-between px-5 h-[4rem]">
      <p>Order.uk Copyright 2024, All Rights Reserved.</p>
      <ul class="flex gap-5">
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
  </div>
</template>
