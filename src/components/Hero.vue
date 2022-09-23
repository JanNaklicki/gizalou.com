<template>
  <b-container fluid class="hero p-0">
    <img src="../assets/ilonka.png" alt="" />
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss">
.hero {
  background-color: white;
  height: 95vh;
  overflow: hidden;
  position: sticky;
  top: 0;
  z-index: 0;
  @include media-breakpoint-down(md) {
    height: 70vh;
  }
  img {
    width: 100%;
    height: 100%;
    @include media-breakpoint-down(md) {
      object-fit: cover;
    }
  }
}
</style>
