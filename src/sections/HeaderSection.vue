<script setup lang="ts">
import ColouredBlob from '../components/ColouredBlob.vue'
import RedSmile from '@/assets/RedSmile.jpeg'
import LottieWoods from '@/assets/LottieWoods.jpeg'
</script>

<template>
  <header
    class="container relative flex h-screen snap-center snap-always flex-col items-center justify-end space-y-1 overflow-hidden px-6 py-8">
    <div class="absolute top-12 aspect-video h-28 w-[90%] max-w-xs">
      <div class="relative h-full w-full">
        <ColouredBlob
          class="absolute w-[200%] max-w-xl -translate-y-[15%] -translate-x-1/4 -rotate-45" />
        <img
          :src="LottieWoods"
          class="absolute -right-10 top-[48%] w-[66%] max-w-[220px] -rotate-6 shadow-2xl" />
        <img
          :src="RedSmile"
          class="absolute -left-12 top-[25%] w-[70%] max-w-[220px] rotate-12 shadow-2xl" />
      </div>
    </div>

    <div class="z-10 flex w-full flex-col space-y-1">
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
