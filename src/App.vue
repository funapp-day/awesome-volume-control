<template>
  <div class="index">
    <atom-video-player
      src="/lorem-video.mp4"
      width="400"
      height="250"
      autoplay
      loop
    ></atom-video-player>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import AtomVideoPlayer from '@/components/atoms/VideoPlayer.vue';

export default defineComponent({
  components: {
    AtomVideoPlayer,
  },
});
</script>
