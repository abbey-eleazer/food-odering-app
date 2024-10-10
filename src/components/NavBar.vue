<script setup></script>

<template>
  <nav class="fixed w-[79vw] mx-auto mt-12 bg-white py-5 z-50">
    <div class="flex items-center justify-between">
      <img src="../assets/icons/LOGO 1.png" alt="" class="">
      
        <ul class="flex items-center gap-6">
          <li >
            <router-link active-class="bg-orange-400 py-2 px-8 text-white" class="hover:bg-orange-400 py-2 px-8 rounded-full hover:text-white" to="/">Home</router-link>
          </li>
          <li >
            <router-link class="hover:bg-orange-400 py-2 px-8 rounded-full hover:text-white" to="">Browse Menu</router-link>
          </li>
          <li >
            <router-link class="hover:bg-orange-400 py-2 px-8 rounded-full hover:text-white" to="">Special Offers</router-link>
          </li>
          <li >
            <router-link active-class="bg-orange-400 py-2 px-8 text-white" class="hover:bg-orange-400 py-2 px-8 rounded-full hover:text-white" to="/restaurants">Restaurants</router-link>
          </li>
          <li >
            <router-link class="hover:bg-orange-400 py-2 px-8 rounded-full hover:text-white" to="">Track order</router-link>
          </li>
          <div>
            <button class=" bg-black text-white rounded-full py-4 px-6">
              <router-link to="" class="flex items-center justify-between">
               <img src="../assets/icons/Male User.png" alt="user">
              <p>Login/Signup</p>
            </router-link>
            </button>
          </div>
        </ul>
     
    </div>
  </nav>
</template>