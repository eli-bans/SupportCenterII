<template>
    <section class="relative w-[1222px] h-[641px] mx-auto bg-gradient-to-t from-[#818498] to-[#818498] flex items-center justify-between">
      <!-- Image Rectangle -->
      <div class="absolute w-[537px] h-[593px] top-[26px] right-[34px] bg-gradient-to-t from-[#818498] to-[#818498] rounded-tl-[20px] z-10">
        <img src="../assets/journey.jpg" alt="Journey Image" class="w-full h-full object-cover rounded-tl-[20px]" />
      </div>
      <!-- Text Content -->
      <div class="absolute left-[181px] top-[26px] text-left text-white">
        <h1 class="font-lato text-[55px] font-medium leading-[48px] mb-8" style="width: 477px; height: 113px;">
          Start your journey with us.
        </h1>
        <p class="font-lato text-[35px] font-medium leading-[33px] mb-8" style="width: 477px; height: 75px;">
          Book with one of our seasoned mentors today!
        </p>
        <a href="#" class="inline-block bg-[#B83838] text-white font-lato font-bold text-[16px] leading-[18.76px] px-6 py-3 rounded-tr-lg" style="width: 153.56px; height: 43px;">
          Book a session
        </a>
      </div>
    </section>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    name: 'JourneySection',
  });
  </script>
  
  <style scoped>
  /* Add any additional scoped styles if needed */
  </style>
  