<script setup lang="ts">
import { VIDEO_YOUTUBE_CERISE } from '@/constants'
</script>

<template>
  <section class="section">
    <div class="flex flex-col items-center justify-end space-y-20">
      <iframe
        :src="VIDEO_YOUTUBE_CERISE"
        title="The Secret of Cerise by Tipsy Cow Productions"
        class="aspect-video w-full shadow-2xl"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>

      <div>
        <h2 class="text-4xl">Writing</h2>
        <p class="text-xl">
          Ut sagittis ipsum ac nulla sagittis, quis venenatis arcu varius. Morbi
          quis nulla vel ante tincidunt pretium. Suspendisse sit amet elit
          congue orci aliquam elementum.
        </p>
        <p class="text-xl">
          Mauris id metus in leo porttitor accumsan. Vivamus vel ligula aliquam,
          tincidunt ante vitae, porta diamerp.
        </p>
      </div>
    </div>
  </section>
</template>
