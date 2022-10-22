<script setup lang="ts">
import KneesUps from '@/assets/KneesUp.jpeg'
</script>

<template>
  <section
    class="overflow--visible container relative flex h-screen snap-start flex-col items-start justify-start space-y-20 px-6 py-16">
    <h2 class="text-4xl font-light lowercase text-gray-700">Acting</h2>
    <p class="text-xl font-light lowercase text-gray-700">
      Ut sagittis ipsum ac nulla sagittis, quis venenatis arcu varius. Morbi
      quis nulla vel ante tincidunt pretium. Suspendisse sit amet elit congue
      orci aliquam elementum. Mauris id metus in leo porttitor accumsan. Vivamus
      vel ligula aliquam, tincidunt ante vitae, porta diamerp.
    </p>

    <img
      :src="KneesUps"
      class="absolute right-0 -bottom-12 w-2/3 max-w-xs rotate-[20deg]" />
  </section>
</template>
