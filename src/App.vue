<template>
  <div>
    <Header />
    <Hero />
    <div class="content">
      <Gallery />
      <Branding />
      <LifeOfArt />
      <About />
      <Footer/>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Hero from "./components/Hero.vue";
import Gallery from "./components/Gallery.vue";
import Branding from "./components/Branding.vue";
import LifeOfArt from "./components/LifeOfArt.vue";
import About from "./components/About.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: { Header, Hero, Gallery, Branding, LifeOfArt, About, Footer },
};
</script>

<style lang="scss">
@import "~@/assets/scss/vendors/bootstrap-vue/index";
html,
body {
  scroll-behavior: smooth;
  background-color: black !important;
  margin: 0;
  padding: 0;
  font-family: "Montserrat", sans-serif;
}
.content {
  position: relative;
  z-index: 90;
  margin-top: 95vh;
  @include media-breakpoint-down(md) {
    margin-top: 94vh;
  }
}
</style>
