<template>
  <picture>
    <source srcset="https://github.githubassets.com/images/modules/site/about/octocats.webp" type="image/webp">
    <img src="https://github.githubassets.com/images/modules/site/about/octocats.png" v-bind="$attrs">
  </picture>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
export default defineComponent({
  inheritAttrs: false,
});
</script>
