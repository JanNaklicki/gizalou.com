<template>
  <b-container id="about" fluid class="about pt-4">
    <b-row>
      <b-col class="about__description">
        <b-row class="mb-4">
          <b-col>
            <h2 class="mb-5 h1">ABOUT ME</h2>
            <h3 class="h3">Me myself and I</h3>
            <p class="mt-4">
              I study Industrial Design Engineering at Politechnika Krakowska
              which means that I work with different materials and I have to use
              all different kinds of skills. As a little advert for my Uni I
              will add that half of my classes take place at ASP in Cracow so we
              really know how to make things artsy.
            </p>
          </b-col>
        </b-row>
        <b-row>
          <b-col>
            <h3 class="h3">In private</h3>
            <h4 class="h4">Meet me on my insta! <a href="">(@giza.lou)</a></h4>
            <p class="mt-4">
              I really love sharing my life with you, creating community full of
              many different talents and passions. That energy is something that
              gives me the inspiration to create my art!
            </p>
          </b-col>
        </b-row>
      </b-col>
      <b-col cols="12" md="5">
        <b-img src="../assets/about/julka.jpg" fluid />
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.about {
  background-color: white;
  @include media-breakpoint-up(md) {
    padding: 0 10%;
  }
  a {
    color: #df0160;
    text-decoration: none;

    &:visited {
      color: #fc1d72;
      text-decoration: none;
    }
    &:hover {
      opacity: 0.7;
      text-decoration: none;
    }
    &:active {
      opacity: 1;
      text-decoration: none;
    }
  }
  &__description {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
}
</style>
