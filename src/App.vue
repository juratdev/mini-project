<script setup>
  import { ChipIcon, MenuAlt3Icon } from '@heroicons/vue/outline'
</script>

<template>
  <div class="w-full min-h-screen px-6 py-6 bg-primary">
    <!-- LOGO -->
    <header class="flex items-center justify-between text-white">
      <div class="flex space-x-2">
        <span>
          <ChipIcon class="w-6 h-6" />
        </span>
        <span class="font-bold">ENDER</span>
      </div>
      <div>
        <MenuAlt3Icon class="w-6 h-6 cursor-pointer" />
      </div>
    </header>
    <!-- MAIN -->
    <main class="flex flex-col mt-16 space-y-12">
      <h1 class="text-white text-4xl font-bold">Congratulations! You've <br /> won the Competition!👏</h1>
      <div class="grid grid-cols-1 gap-4 sm:grid-cols-3">
        <div class="h-24">
          <img class="object-cover w-full h-full" src="./assets/1.jpg" alt="">
        </div>
        <div class="h-24">
          <img class="object-cover w-full h-full" src="./assets/2.jpg" alt="">
        </div>
        <div class="h-24">
          <img class="object-cover w-full h-full" src="./assets/3.jpg" alt="">
        </div>
      </div>
      <p class="text-white">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Possimus quos repellendus non, hic
        illum ipsam, sit vitae ipsum aperiam <span class="text-marked">magni, asperiores similique repellat</span>
        eligendi placeat quas
        quisquam consequatur architecto earum. </p>
      <div class="px-6 py-4 bg-secondary text-white flex justify-between items-center border border-gray-700">
        <div class="flex flex-col space-y-2">
          <span class="text-gray-400">You won</span>
          <span class="text-2xl font-bold">+$75.00</span>
          <span class="text-sm text-gray-400">Account Balance: $175</span>
        </div>
        <div>
          <a class="uppercase px-6 py-2 font-bold text-black bg-white rounded-sm" href="#">View Result</a>
        </div>
      </div>
      <div class="text-white">
        <span class="text-sm text-gray-400">" Elon Musk, CEO of SpaceX</span>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum temporibus expedita blanditiis repudiandae
          deserunt quod quam explicabo accusamus doloremque porro.</p>
        <div class="border border-gray-800 mt-8"></div>
        <div class="flex space-x-2 mt-9 text-gray-400">
          <span>
            <ChipIcon class="w-5 h-5" />
          </span>
          <span class="text-sm">ENDER</span>
        </div>
      </div>
    </main>
  </div>
</template>