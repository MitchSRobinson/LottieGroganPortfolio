<script setup lang="ts">
import { VIDEO_YOUTUBE_CERISE } from '@/constants'
</script>

<template>
  <section
    class="container relative flex h-screen snap-center snap-always flex-col justify-end overflow-visible px-6 py-8">
    <div class="flex flex-col items-start justify-end space-y-20">
      <h2 class="text-4xl font-light lowercase text-gray-700">Writing</h2>
      <div>
        <p class="text-xl font-light text-gray-700">
          Ut sagittis ipsum ac nulla sagittis, quis venenatis arcu varius. Morbi
          quis nulla vel ante tincidunt pretium. Suspendisse sit amet elit
          congue orci aliquam elementum.
        </p>
        <p class="text-xl font-light text-gray-700">
          Mauris id metus in leo porttitor accumsan. Vivamus vel ligula aliquam,
          tincidunt ante vitae, porta diamerp.
        </p>
      </div>
    </div>

    <div
      class="absolute top-[15%] left-[5%] aspect-video w-[90%] max-w-xl shadow-2xl">
      <iframe
        :src="VIDEO_YOUTUBE_CERISE"
        title="The Secret of Cerise by Tipsy Cow Productions"
        class="aspect-video w-full"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen></iframe>
    </div>
  </section>
</template>
