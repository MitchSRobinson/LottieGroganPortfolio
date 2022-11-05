<script setup lang="ts">
import LottiePuppetry from '@/assets/LottiePuppetry.jpg'
</script>

<template>
  <section>
    <h2 class="text-4xl">Puppetry</h2>

    <div>
      <p class="text-xl">
        Suspendisse sit amet elit congue orci aliquam elementum. Ut sagittis
        ipsum ac nulla sagittis, quis venenatis arcu varius. Morbi quis nulla
        vel ante tincidunt pretium.
      </p>

      <p class="text-xl">
        Morbi quis nulla vel ante tincidunt pretium. Vivamus vel ligula aliquam,
        tincidunt ante vitae, porta diamerp.
      </p>
    </div>

    <img
      :src="LottiePuppetry"
      class="absolute -left-[10%] bottom-0 max-h-[40%] w-full max-w-lg -rotate-12" />
  </section>
</template>
