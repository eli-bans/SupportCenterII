<template>
  <div id="app">
    <Navbar />
    <IntroSection />
    <OfferSection />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Navbar from './components/Navbar.vue';
import IntroSection from './components/IntroSection.vue';
import OfferSection from './components/OfferSection.vue';

export default defineComponent({
  name: 'App',
  components: {
    Navbar,
    IntroSection,
    OfferSection,
  },
});
</script>

<style>
/* Additional global styles if needed */
</style>
