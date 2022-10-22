<script setup lang="ts">
import FacebookIcon from '@/components/Icons/FacebookIcon.vue'
import InstagramIcon from '@/components/Icons/InstagramIcon.vue'
import TiktokIcon from '@/components/Icons/TiktokIcon.vue'
import YoutubeIcon from '@/components/Icons/YoutubeIcon.vue'
</script>

<template>
  <section
    class="container flex h-screen max-h-screen w-screen snap-start snap-always flex-col justify-between overflow-hidden">
    <div
      class="flex flex-col items-start justify-start space-y-8 px-6 pt-20 pb-4">
      <h2 class="text-4xl font-light lowercase text-gray-700">Hire me</h2>
      <p class="text-xl font-light text-gray-700">
        To get in touch send pigeon mail to 123 Brick Ln, Dot Com
      </p>
    </div>

    <footer
      class="flex w-full flex-col items-center justify-center bg-footer px-4 py-16 pb-32">
      <span class="text-2xl font-thin text-gray-300">Lottie Grogan</span>
      <span class="text-lg font-thin text-gray-300"
        >Delaney Grey Management</span
      >

      <div class="flex w-fit space-x-4 pt-4">
        <FacebookIcon height="32" width="32" />
        <InstagramIcon height="32" width="32" />
        <TiktokIcon height="32" width="32" />
        <YoutubeIcon height="32" width="32" />
      </div>
    </footer>
  </section>
</template>
