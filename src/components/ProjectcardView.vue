<script>
// import { slideLeft } from '@/views/ProjectsView.vue'
export default {
  props: {
    data: {
      type: String,
      required: true,

    },
  },
  data(){
    // return slideLeft()
  }

};
</script>

<template>

  <div class="text-white p-8 card lg:w-1/4 bg-[#1A1A2E]/50">

    <div class="flex flex-col">
      <img :src="data.image" :alt="data.altimage" class="rounded-lg"/>
      <h1 class="text-3xl my-4 text-center font-semibold">{{ data.title }}</h1>
      <p class="mb-4">{{ data.description }}</p>
    </div>
    <div class="flex flex-col lg:flex-row justify-between mx-4">
<!--      <button class="bg-[#0F3460] rounded-xl my-2 shadow-sm shadow-[#1a59a5] shadow-inner">See more</button>-->
        <a :href="data.githuburl"> <button class="bg-[#0F3460] rounded-xl mb-2 w-44 shadow-lg shadow-black shadow-inner px-2 py-4 hover:bg-[#0F3460]/20">Github Repository</button></a>
        <a :href="data.websiteurl"> <button class="bg-[#0F3460] rounded-xl w-44 shadow-lg shadow-black shadow-inner px-2 py-4 hover:bg-[#0F3460]/20">Website</button></a>
    </div>
    <div class="text-sm">
      <h4>Used languages: {{data.languages}}</h4>
      <h4>Used frameworks: {{data.frameworks}}</h4>
    </div>
  </div>
</template>
