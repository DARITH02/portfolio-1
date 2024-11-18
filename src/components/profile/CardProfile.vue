<script setup>
import AboutMe from "./AboutMe.vue";
import Profil from "./Profile.vue"
</script>

<template>
  <div class="w-full md:w-4/5 lg:w-3/5 m-auto bg-blue-300  rounded-md">
    <div class="w-full flex gap-3">
      <div class="w-2/5 lg:w-1/4 md:w-2/5  bg-blue-400 rounded-[25px]">
        <Profil/>
      </div>
      <div class="w-3/5 lg:w-3/4 md:w-3/5" >
        <AboutMe />
      </div>
    </div>
  </div>
</template>
