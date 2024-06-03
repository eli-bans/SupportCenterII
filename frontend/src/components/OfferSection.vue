<template>
    <section class="relative w-full py-16">
      <div class="text-center mb-12">
        <h2 class="font-lato text-[50px] font-medium leading-[18.76px] text-left text-[#000000] mx-auto" style="width: 341px; height: 59px;">
          What We Offer
        </h2>
        <p class="font-lato text-[24px] font-normal leading-[18.76px] text-left text-[#000000] mx-auto" style="width: 324px; height: 35px;">
          Courses and Languages
        </p>
      </div>
      <div class="flex flex-wrap justify-center gap-6 mt-8">
        <InfoCard text="Data Structures and Algorithms" icon="path/to/icon1.png" />
        <InfoCard text="Web Development" icon="path/to/icon2.png" />
        <InfoCard text="Machine Learning" icon="path/to/icon3.png" />
        <InfoCard text="Database Systems" icon="path/to/icon4.png" class="mt-8" />
        <InfoCard text="Artificial Intelligence" icon="path/to/icon5.png" class="mt-8" />
      </div>
    </section>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  import InfoCard from './InfoCard.vue';
  
  export default defineComponent({
    name: 'OfferSection',
    components: {
      InfoCard,
    },
  });
  </script>
  
  <style scoped>
  /* Add any additional scoped styles if needed */
  </style>
  