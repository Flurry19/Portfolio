<template>
  <nav>
    <div class="block flex flex-wrap justify-center lg:justify-end align-middle mx-36 text-2xl lg:absolute lg:right-0">

    <div class="block navbar flex flex-col lg:flex-row text-center text-white font-semibold z-10">
      <div class="block py-2 px-3"><router-link to="/">Home</router-link></div>
      <div class="block py-2 px-3"><router-link to="/about">About</router-link></div>
      <div class="block py-2 px-3"><router-link to="/projects">Projects</router-link></div>
      <div class="block py-2 px-3"><router-link to="/skills">Skills</router-link></div>
    </div>
<!--      <div class="hamburger lg:hidden">-->
<!--        <span class="block w-6 h-1 m-1 bg-white"></span>-->
<!--        <span class="block w-6 h-1 m-1 bg-white"></span>-->
<!--        <span class="block w-6 h-1 m-1 bg-white"></span>-->
<!--      </div>-->
<!--      <button onclick="openNavbar()" class="">Olllaaaa</button>-->
    </div>
  </nav>
</template>
<script>
export default {
  methods: {

  }
}

</script>