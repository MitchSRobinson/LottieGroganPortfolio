<script setup lang="ts">
import KneesUps from '@/assets/KneesUp.jpeg'
</script>

<template>
  <section
    class="container relative flex h-screen snap-start snap-always flex-col items-start justify-start space-y-8 overflow-visible px-6 py-8 pb-16">
    <h2 class="text-4xl font-light lowercase text-gray-700">Acting</h2>
    <p class="text-xl font-light lowercase text-gray-700">
      Ut sagittis ipsum ac nulla sagittis, quis venenatis arcu varius. Morbi
      quis nulla vel ante tincidunt pretium. Suspendisse sit amet elit congue
      orci aliquam elementum. Mauris id metus in leo porttitor accumsan.
    </p>

    <img
      :src="KneesUps"
      class="absolute -bottom-16 right-0 w-2/3 max-w-xs rotate-[20deg]" />
  </section>
</template>
