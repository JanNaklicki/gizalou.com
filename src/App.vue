<template>
  <div>
    <Header />
    <Hero />
    <Gallery />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Hero from "./components/Hero.vue";
import Gallery from "./components/Gallery.vue";

export default {
  name: "App",
  components: { Header, Hero, Gallery },
};
</script>

<style lang="scss">
@import "~@/assets/scss/vendors/bootstrap-vue/index";
html,
body {
  background-color: black;
  margin: 0;
  padding: 0;
  font-family: "Montserrat", sans-serif;
}
</style>
