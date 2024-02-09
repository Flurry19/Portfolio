<script setup>

import { RouterLink, RouterView } from 'vue-router'
import NavbarView from "@/components/NavbarView.vue";
</script>

<template>

  <html>
  <body class="h-full m-0 p-0 bg-[#1A1A2E] font-quicksand">
<!--      <div class="triangleleft"></div>-->
<!--      <div class="triangleright right-0"></div>-->
<!--      <div class="triangleleft2"></div>-->
<!--      <div class="triangleright2 right-0"></div>-->
<!--      <div class="triangleleft3"></div>-->
<!--      <div class="triangleright3 right-0"></div>-->
<!--      <div class="triangleleft4"></div>-->
<!--      <div class="triangleright4 right-0"></div>-->
<!--  <div class="bg-gradient-to-br"></div>-->
  <header>
<NavbarView />
  </header>

  <RouterView />
  </body>
  </html>
</template>
