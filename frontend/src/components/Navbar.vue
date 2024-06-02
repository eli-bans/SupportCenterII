<template>
    <nav class="absolute w-[1440px] h-[72px] left-0 top-0 bg-[#404041] flex items-center justify-between px-4 z-50">
      <div class="flex items-center">
        <p class="text-[#FFFFFFCC] font-lato font-extrabold text-[24px] leading-[20px]">
          Support Center
        </p>
      </div>
      <div class="flex items-center gap-[21px]">
        <button 
          :class="homeClass" 
          @click="setActive('home')"
          class="text-white font-lato font-semibold text-[16px] leading-[18.76px] w-[90.56px] h-[43px] rounded">
          Home
        </button>
        <a 
          href="#" 
          @click="setActive('aboutUs')" 
          :class="aboutUsClass" 
          class="text-white font-lato font-medium text-[16px] leading-[20px] px-2 py-1">
          About Us
        </a>
      </div>
    </nav>
  </template>
  
  <script lang="ts">
  import { defineComponent, ref, computed } from 'vue';
  
  export default defineComponent({
    name: 'Navbar',
    setup() {
      const activeButton = ref<string>('home');
  
      const setActive = (button: string) => {
        activeButton.value = button;
      };
  
      const homeClass = computed(() => {
        return activeButton.value === 'home' ? 'bg-[#B83838]' : '';
      });
  
      const aboutUsClass = computed(() => {
        return activeButton.value === 'aboutUs' ? 'bg-[#B83838]' : '';
      });
  
      return {
        activeButton,
        setActive,
        homeClass,
        aboutUsClass,
      };
    },
  });
  </script>
  
  <style scoped>
  /* Add any additional scoped styles if needed */
  </style>
  