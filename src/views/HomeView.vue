<template>
  <div class="home">
    <Navbar />
    <Hero />
    <Kategori />
    <Resep />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Hero from "@/components/Hero.vue";
import Kategori from "@/components/Kategori.vue";
import Resep from "@/components/Resep.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "HomeView",
  components: {
    Navbar,
    Hero,
    Kategori,
    Resep,
    Footer,
  },
};
</script>
