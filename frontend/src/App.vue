<template>
  <div id="app">
    <Navbar />
    <IntroSection />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Navbar from './components/Navbar.vue';
import IntroSection from './components/IntroSection.vue';

export default defineComponent({
  name: 'App',
  components: {
    Navbar,
    IntroSection,
  },
});
</script>

<style>
/* Additional global styles if needed */
</style>

