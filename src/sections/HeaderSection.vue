<script setup lang="ts">
import HeaderImage from '@/assets/HeaderImage.png'
</script>

<template>
  <header class="section items-center justify-end">
    <img
      :src="HeaderImage"
      class="absolute top-[calc(35%_-_350px)] left-[calc(58%_-_350px)] w-[700px] max-w-none" />

    <div class="z-10 w-full">
      <h1 class="text-5xl">Lottie Grogan</h1>
      <h2 class="text-4xl">Professional Idiot</h2>
      <h3 class="text-xl">actor writer puppeteer funny-ish</h3>
    </div>
  </header>
</template>
