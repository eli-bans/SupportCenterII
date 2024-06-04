<template>
    <div class="relative w-[265px] h-[361px] bg-[#EEEEEE] rounded-tr-[15px]">
      <div class="absolute w-[213px] h-[252px] bg-[#EEEEEE] rounded-tr-[15px] top-[26px] left-[25px] overflow-hidden">
        <img :src="image" alt="Tutor Image" class="w-full h-full object-cover" />
      </div>
      <div class="absolute w-[102px] h-[19px] top-[294px] left-[82px]">
        <p class="font-lato text-[20px] font-semibold leading-[18.76px] text-left text-[#000000]">
          {{ name }}
        </p>
      </div>
    </div>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    name: 'TutorProfile',
    props: {
      image: {
        type: String,
        required: true,
      },
      name: {
        type: String,
        required: true,
      },
    },
  });
  </script>
  
  <style scoped>
  /* Add any additional scoped styles if needed */
  </style>
  