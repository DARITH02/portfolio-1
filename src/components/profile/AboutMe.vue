<script setup>
import SvgIcon from "@jamescoyle/vue-icon";

import {
  mdiLanguageCss3,
  mdiLanguageJavascript,
  mdiGithub,
  mdiLanguageHtml5,
  mdiLanguagePhp,
  mdiLanguageCsharp,
} from "@mdi/js";

</script>

<template>
  <div class="w-full md:w-full md:p-3 lg:p-4 p-1 py-7">
    <h1 class="text-4xl font-bold text-blue-950 my-7">About Me</h1>
    <p class="text-justify text-blue-950 font-normal leading-5 text-lg">
      <span class="ml-10"> Lorem</span> ipsum dolor sit amet consectetur,
      adipisicing elit. Voluptate, eius quos dignissimos molestiae qui ab
      eligendi quisquam quia non ratione? Consectetur ut aperiam animi totam
      enim vel rerum optio voluptatibus vero doloribus, tenetur voluptas aliquid
      suscipit omnis et dolor doloremque molestias. Voluptatibus quos officiis
      debitis praesentium, modi nemo voluptatum illo. Lorem, ipsum dolor sit
      amet consectetur adipisicing elit. Voluptates vero quam debitis
      perferendis hic dolores repellendus doloribus amet provident facere,
      exercitationem atque culpa adipisci sed sapiente fuga eligendi libero
      delectus porro quasi similique! Enim, inventore ipsum. Ab, consequuntur
      pariatur? Minima fugiat dolorum sit. Quaerat minima quisquam natus debitis
      recusandae explicabo, facilis sit quia corrupti assumenda rem, doloremque,
      eos id itaque laudantium ipsam et cum animi minus officiis expedita nam
    </p>
    <div class="w-full mt-6">
      <h1 class="text-center lg:text-3xl md:text-xl text-lg font-bold text-blue-950">
        Technologies Studied
      </h1>
      <div class="w-full h-auto flex justify-center mt-7">
        <div class="flex gap-3 h-auto items-center">
          <span class="w-10 h-10 p-2 bg-white rounded-3xl overflow-hidden">
            <svg-icon
              class="w-full h-full text-orange-700 rounded-3xl"
              type="mdi"
              :path="mdiLanguageJavascript"
            ></svg-icon>
          </span>
          <span class="w-10 h-10 p-2 bg-white rounded-3xl overflow-hidden">
            <svg-icon
              class="text-red-500"
              type="mdi"
              :path="mdiLanguageCss3"
            ></svg-icon>
          </span>
          <span class="w-10 h-10 p-2 bg-white rounded-3xl overflow-hidden">
            <svg-icon
              class="text-red-500"
              type="mdi"
              :path="mdiLanguageHtml5"
            ></svg-icon>
          </span>
          <span class="w-10 h-10 p-2 bg-white rounded-3xl overflow-hidden">
            <svg-icon
              class="text-red-500"
              type="mdi"
              :path="mdiLanguagePhp"
            ></svg-icon>
          </span>
          <span class="w-10 h-10 p-2 bg-white rounded-3xl overflow-hidden">
            <svg-icon
              class="text-red-500"
              type="mdi"
              :path="mdiLanguageCsharp"
            ></svg-icon>
          </span>
        </div>
      </div>
      <div class="w-full flex justify-center mt-5">
        <div class="flex gap-5">
          <button class="text-lg border border-blue-300 rounded-xl bg-blue-400 text-white py-2 px-3">My Project</button>
          <button class="text-lg border-blue-300 rounded-xl bg-blue-400 text-white py-2 px-3">My Resume</button>

        </div>
      </div>
    </div>
  </div>
</template>
