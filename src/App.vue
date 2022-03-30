<template>
  <div>
    <!-- <Header />x -->
    <!-- <Hero /> -->
    <main>
      <Gallery />
    </main>
    <footer></footer>
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
  margin: 0;
  padding: 0;
  background-color: #040007;
}
main {
  background-image: url("./assets/purple.jpeg");
  background-size: cover;
  width: 100%;
}
.devider {
  height: 80vh;
  margin-top: -50px;
  z-index: 0;
  // background-color: #8d67ca;
}
</style>
