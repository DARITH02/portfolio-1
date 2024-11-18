<script setup>
import SvgIcon from "@jamescoyle/vue-icon";
import {mdiAccount, mdiGithub,mdiInstagram,mdiLinkedin, mdiTwitter} from "@mdi/js"


</script>

<template>
  <div class="w-full py-5">
    <div class="w-full flex justify-center lg:h-44 h-32 md:h-28 ">
      <img
        class="rounded-[50%] lg:h-full h-32 md:h-full"
        src="https://i.pinimg.com/736x/b5/78/5a/b5785af39d097409d685d68c242c146a.jpg"
        alt=""
      />
    </div>
    <div class="w-full py-4">
      <h1 class="text-center text-white font-bold text-sm xl:text-xl">
        VEN CHANDARITH
      </h1>
    </div>
    <div class="w-full py-1">
      <h3
        class="text-center text-white md:font-medium font-thin text-sm xl:text-sm"
      >
        SoftWare Developer
      </h3>
    </div>
    <div class="w-full flex flex-col justify-center items-center gap-2">
      <div class="w-2/6 h-auto">
        <div class="w-2/4 lg:w-2/5 md:w-2/6 m-auto">
          <a href="">
            <svg-icon class="w-full h-auto text-gray-900" type="mdi" :path="mdiGithub"></svg-icon>
            <span
              class="text-white lg:font-medium lg:text-sm text-xs w-full flex justify-center"
            >
              GitHub
            </span>
          </a>
        </div>
      </div>
      <div class="w-2/6 h-auto">
        <div class="w-2/4 lg:w-2/5 md:w-2/6 m-auto">
          <a href="" class="text-2xl">

            <!-- <svg-icon class="w-16 h-10 text-blue-700"   type="mdi" :path="mdiAccount"></svg-icon> -->
            <svg-icon class="w-full h-auto text-gray-900" type="mdi" :path="mdiLinkedin"></svg-icon>
            <span
              class="text-white lg:font-medium lg:text-sm text-xs w-full flex justify-center"
            >
              LinkedIn
            </span>
          </a>
        </div>
      </div>
      <div class="w-2/6 h-auto">
        <div class="w-2/4 lg:w-2/5 md:w-2/6 m-auto">
          <a href="">
          <svg-icon class="w-full h-auto text-gray-800" type="mdi" :path="mdiTwitter"></svg-icon>
            <span
              class="text-white lg:font-medium lg:text-sm text-xs w-full flex justify-center"
            >
              Twiter
            </span>
          </a>
        </div>
      </div>
      <div class="w-2/6 h-auto">
        <div class="w-2/4 lg:w-2/5 md:w-2/6 m-auto">
          <a href="">
           <svg-icon class="w-full h-auto text-gray-800" type="mdi" :path="mdiInstagram"></svg-icon>
            <span
              class="text-white lg:font-medium lg:text-sm text-xs w-full flex justify-center"
            >
              Instagram
            </span>
          </a>
        </div>
      </div>
      
    </div>
  </div>
</template>
