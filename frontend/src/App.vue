<template>
  <div id="app">
    <Navbar />
    <IntroSection />
    <OfferSection />
    <TutorSection />
    <Journey />

  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Navbar from './components/Navbar.vue';
import IntroSection from './components/IntroSection.vue';
import OfferSection from './components/OfferSection.vue';
import TutorSection from './components/TutorSection.vue';
import Journey from './components/Journey.vue';

export default defineComponent({
  name: 'App',
  components: {
    Navbar,
    IntroSection,
    OfferSection,
    TutorSection,
    Journey,
    
  },
});
</script>

<style>
/* Additional global styles if needed */
</style>
