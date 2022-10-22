<script setup lang="ts">
import ColouredBlob from '../components/ColouredBlob.vue'
import RedSmile from '@/assets/RedSmile.jpeg'
import LottieWoods from '@/assets/LottieWoods.jpeg'
</script>

<template>
  <header
    class="container relative flex h-screen snap-start flex-col items-center justify-between space-y-1 overflow-visible px-6 py-16">
    <div class="relative top-0 aspect-video h-1/2 w-[90%] max-w-xs">
      <ColouredBlob class="absolute top-[5%] -left-12 w-[150%] -rotate-45" />
      <img
        :src="LottieWoods"
        class="absolute -right-16 top-[40%] w-[60%] -rotate-6 shadow-2xl" />
      <img
        :src="RedSmile"
        class="absolute -left-12 top-[20%] w-[70%] rotate-12 shadow-2xl" />
    </div>

    <div class="flex w-full flex-col space-y-1">
      <h1 class="text-5xl font-light lowercase text-gray-700">Lottie Grogan</h1>
      <h2 class="text-4xl font-light lowercase text-gray-700">
        Professional Idiot
      </h2>
      <h3 class="text-xl font-light lowercase text-gray-700">
        actor writer puppeteer funny-ish
      </h3>
    </div>
  </header>
</template>
