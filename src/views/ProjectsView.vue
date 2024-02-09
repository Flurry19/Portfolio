<script>
import ProjectcardView from "@/components/ProjectcardView.vue";

export default {
  components: { ProjectcardView },
  data() {
    return {
      projects: [
        {
          title: "Allergiescanner",
          description:
            "For this project I made a webapplication with which you can fill in your allergies and then scan a barcode of a product and see if it contains your allergies. I made this with a group for school for MEE Rotterdam Rijnmond. This is designed for people with a mild intellectual disability.",
          image: "/images/img_2.png",
          altimage: "A screenshot from the made application Allergiescanner",
          githuburl: "https://github.com/Flurry19/TLE1/",
          websiteurl: "https://allergiescannermee.nl/",
          frameworks: "Vue, Tailwind",
          languages: "Javascript, HTML, CSS",
        },


      ],
    };
  },
  methods: {
  },
};

</script>
<template>
  <main>
    <div class=" min-h-screen lg:mx-12">
      <h1 class="text-white text-center font-bold text-3xl py-6 lg:py-12">Projects</h1>


  <div class="lg:flex lg:flex-row lg:flex-wrap">
    <ProjectcardView
      v-for="project in projects"
      :key="projects.title"
      :data="project"
    />
  </div>
    </div>
  </main>
</template>
