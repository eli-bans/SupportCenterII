<template>
    <section class="relative w-[1440px] h-[676px] bg-gradient-to-b from-transparent to-black z-0">
      <img src="../assets/IMG_1781.jpeg" alt="Background Image" class="absolute inset-0 w-full h-full object-cover" />
      <div class="absolute inset-0 flex flex-col items-center justify-center text-center z-10 px-4">
        <h1 class="text-[#FFFFFF] font-lato font-medium text-[59px] leading-[20px] tracking-[-0.01em] mb-4" style="width: 739px; height: 76px; top: 209px; left: 350px;">
          We solve problems, together
        </h1>
        <p class="text-[#FFFFFF] font-lato font-normal text-[18px] leading-[20px] tracking-[-0.01em] mb-8" style="width: 690px; height: 40px; top: 298px; left: 374px;">
          Stuck on a coding problem? We get it. Support Center is your community to unravel CS challenges and level up your coding skills.
        </p>
        <a href="#" class="bg-[#B83838] text-white font-lato font-bold text-[16px] leading-[18.76px] px-6 py-3 rounded-tr-lg" style="width: 150px; height: 43px;">
          Learn more
        </a>
      </div>
    </section>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    name: 'IntroSection',
  });
  </script>
  
  <style scoped>
  /* Add any additional scoped styles if needed */
  </style>
  