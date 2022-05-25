<template>
  <video
    v-bind="{ ...$attrs }"
    :src="src"
  />
</template>

<script lang="ts">
import { defineComponent, PropType } from 'vue'

export default defineComponent({
  props: {
    src: {
      type: String as PropType<string>,
      required: false,
      default: null,
    },
  },
});
</script>

