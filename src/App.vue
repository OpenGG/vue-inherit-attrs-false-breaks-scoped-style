<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import AttrsComp from './components/AttrsComp.vue';
import InheritAttrsComp from './components/InheritAttrsComp.vue';
</script>

<template>
  <h2>inheritAttrs=true works perfectly.</h2>
  <InheritAttrsComp class="test" />

  <h2>inheritAttrs=fase breaks scoped style.</h2>
  <AttrsComp class="test" />
</template>

<style scoped>
.test {
  width: 90vw;
  border: 1px solid red;
}
</style>
