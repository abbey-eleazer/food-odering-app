<script setup>
</script>

<template>
  <div class=" bg-gray-200">
  <div class="px-24 mt-24 py-12 flex items-center justify-between ">
    <h2 class="text-2xl font-bold">Know more about us!</h2>
    <nav >
      <ul class="flex text-lg items-center gap-2">
        <li class="" >
          <router-link active-class="border border-orange-400 py-2 px-8 text-orange-400" class=" hover:border border2-orange-400 py-2 px-8 rounded-full hover:text-orange-400" to="/">Frequent Questions</router-link>
        </li>
        <li >
          <router-link class=" hover:border border-orange-400  py-2 px-8 rounded-full hover:text-orange-400" to="">Who we are?</router-link>
          </li>
          <li >
            <router-link class="hover:border border-orange-400 py-2 px-8 rounded-full hover:text-orange-400" to="">Partner Program</router-link>
          </li>
          <li >
            <router-link class="hover:border border-orange-400 py-2 px-8 rounded-full hover:text-orange-400" to="">Help & Support</router-link>
          </li>
        </ul>
      </nav>
    </div>
    <div class="">
  <div class="bg-black/90 p-8 flex justify-between rounded-lg">
    <!-- QUESTIONS  -->
     <div class="flex items-center justify-center">
      <ul class="text-center w-[70%]">
        <li >
            <router-link active-class="bg-orange-400 text-black" class=" hover:bg-orange-400 text-white py-2 px-8 rounded-full hover:text-black" to="">How does Order.UK work?</router-link>
          </li>
        <li >
            <router-link class=" hover:bg-orange-400 text-white py-2 px-8 rounded-full hover:text-black" to="">What payment methods are accepted?</router-link>
          </li>
        <li >
            <router-link class=" hover:bg-orange-400 text-white py-2 px-8 rounded-full hover:text-black" to="">Can I track my order in real-time?</router-link>
          </li>
        <li >
            <router-link class=" hover:bg-orange-400 text-white py-2 px-8 rounded-full hover:text-black" to="">Are there any special discounts or promotions available?</router-link>
          </li>
        <li >
            <router-link class=" hover:bg-orange-400 text-white py-2 px-8 rounded-full hover:text-black" to="">Is Order.UK available in my area?</router-link>
          </li>
      </ul>
     </div>

     <!-- CARDS -->
      <div class="flex flex-col items-center justify-center">
      <div class="flex gap-4">
        <div class="w-[14rem] h-[17rem] rounded-xl bg-gray-200 flex flex-col items-center justify-center">
          <h3 class="font-bold pb-4 text-lg">Place an Order!</h3>
          <img src="../assets/icons/order-food 1.png" alt="icon">
          <div class="text-center font-medium">
          <p >Place order through our website or Mobile app</p>
          </div>
        </div>
        <div class="w-[14rem] h-[17rem] rounded-xl bg-gray-200 flex flex-col items-center justify-center">
          <h3 class="font-bold pb-4 text-lg">Track Progress</h3>
          <img src="../assets/icons/food 1.png" alt="icon">
          <div class="text-center font-medium">
          <p >Your can track your order status with delivery time</p>
          </div>
        </div>
        <div class="w-[14rem] h-[17rem] rounded-xl bg-gray-200 flex flex-col items-center justify-center">
          <h3 class="font-bold pb-4 text-lg">Get your Order!</h3>
          <img src="../assets/icons/order 1.png" alt="icon">
          <div class="text-center font-medium">
          <p >Receive your order at a lighting fast speed!</p>
          </div>
        </div>
      </div>
      <p class="text-white text-center w-[60%] mt-12">Order.UK simplifies the food ordering process. Browse through our diverse menu, select your favorite dishes, and proceed to checkout. Your delicious meal will be on its way to your doorstep in no time!</p>
      </div>
    </div>
  </div>
  </div>
</template>
