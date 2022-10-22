<script setup lang="ts">
import LottiePuppetry from '@/assets/LottiePuppetry.jpg'
</script>

<template>
  <section
    class="container relative flex h-screen max-h-screen snap-start snap-always flex-col items-end justify-start space-y-8 overflow-visible px-6 py-8 pt-8 text-right">
    <h2 class="text-4xl font-light lowercase text-gray-700">Puppetry</h2>

    <div>
      <p class="text-xl font-light text-gray-700">
        Suspendisse sit amet elit congue orci aliquam elementum. Ut sagittis
        ipsum ac nulla sagittis, quis venenatis arcu varius. Morbi quis nulla
        vel ante tincidunt pretium.
      </p>

      <p class="text-xl font-light lowercase text-gray-700">
        Morbi quis nulla vel ante tincidunt pretium. Vivamus vel ligula aliquam,
        tincidunt ante vitae, porta diamerp.
      </p>
    </div>

    <img
      :src="LottiePuppetry"
      class="absolute -left-[10%] bottom-0 max-h-[40%] w-full max-w-lg -rotate-12" />
  </section>
</template>
