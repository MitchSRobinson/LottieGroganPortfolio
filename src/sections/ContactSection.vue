<script setup lang="ts">
import FacebookIcon from '@/components/Icons/FacebookIcon.vue'
import InstagramIcon from '@/components/Icons/InstagramIcon.vue'
import TiktokIcon from '@/components/Icons/TiktokIcon.vue'
import YoutubeIcon from '@/components/Icons/YoutubeIcon.vue'
</script>

<template>
  <section class="flex h-screen w-screen flex-col">
    <div
      class="flex grow flex-col space-y-6 px-6 py-8 lg:max-w-xl lg:px-16 lg:py-16">
      <h2 class="text-4xl">Hire me</h2>
      <p class="text-xl">
        To get in touch send pigeon mail to 123 Brick Ln, Dot Com
      </p>
    </div>

    <footer
      class="flex w-full flex-col items-center justify-center bg-footer px-6 py-16 lg:px-16 lg:py-16">
      <div class="flex flex-col items-center">
        <span class="text-4xl font-thin text-gray-300">Lottie Grogan</span>
        <span class="text-xl font-thin text-gray-300"
          >Delaney Grey Management</span
        >
      </div>

      <div class="flex w-fit space-x-4 pt-4">
        <FacebookIcon height="38" width="38" />
        <InstagramIcon height="38" width="38" />
        <TiktokIcon height="38" width="38" />
        <YoutubeIcon height="38" width="38" />
      </div>
    </footer>
  </section>
</template>
