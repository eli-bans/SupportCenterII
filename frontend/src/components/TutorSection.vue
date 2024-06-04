<template>
    <section class="w-full py-16 bg-white flex flex-col items-center">
      <div class="text-center mb-12">
        <h2 class="font-lato text-[50px] font-medium leading-[18.76px] text-[#000000]" style="width: 287px; height: 59px;">
          Top Mentors
        </h2>
      </div>
      <div class="flex flex-wrap justify-center gap-8">
        <TutorCard image="path/to/tutor1.jpg" name="John Doe" />
        <TutorCard image="path/to/tutor2.jpg" name="Jane Smith" />
        <TutorCard image="path/to/tutor3.jpg" name="Alex Johnson" />
        <!-- Add more TutorCard components as needed -->
      </div>
    </section>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  import TutorCard from './TutorCard.vue';
  
  export default defineComponent({
    name: 'MentorSection',
    components: {
      TutorCard,
    },
  });
  </script>
  
  <style scoped>
  /* Add any additional scoped styles if needed */
  </style>
  