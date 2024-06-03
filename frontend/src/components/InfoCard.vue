<template>
    <div class="relative w-[340px] h-[103px] bg-[#EEEEEE] rounded-tr-[15px]">
      <div class="absolute w-[74px] h-[78px] bg-[#FFFFFF] rounded-tr-[15px] top-[13px] left-[16px] flex items-center justify-center">
        <img :src="icon" alt="Icon" class="w-[48px] h-[48px] object-contain" />
      </div>
      <div class="absolute w-[210px] h-[44px] top-[30px] left-[107px]">
        <p class="font-lato text-[24px] font-normal leading-[18.76px] text-left text-[#000000]">
          {{ text }}
        </p>
      </div>
    </div>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    name: 'InfoCard',
    props: {
      text: {
        type: String, // Add the text prop
        required: true,
      },
      icon: {   // Add the icon prop as a url link to the icon
        type: String,
        required: true,
      },
    },
  });
  </script>
  
  <style scoped>
  /* Add any additional scoped styles if needed */
  </style>
  