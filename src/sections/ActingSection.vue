<script setup lang="ts">
import KneesUps from '@/assets/KneesUp.jpeg'
</script>

<template>
  <section>
    <div class="-mb-16 max-w-full space-y-6 lg:max-w-xl">
      <h2 class="pb-12 text-4xl">Acting</h2>

      <p class="text-xl">
        Ut sagittis ipsum ac nulla sagittis, quis venenatis arcu varius. Morbi
        quis nulla vel ante tincidunt pretium.
      </p>

      <p class="text-xl">
        Suspendisse sit amet elit congue orci aliquam elementum. Mauris id metus
        in leo porttitor accumsan.
      </p>
    </div>
    <img
      :src="KneesUps"
      class="absolute -bottom-16 right-0 w-2/3 max-w-xs rotate-[20deg]" />
  </section>
</template>
