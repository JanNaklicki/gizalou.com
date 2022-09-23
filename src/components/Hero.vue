<template>
  <div  class="hero p-0">
    <img src="../assets/ilonka.png" alt="" />
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.hero {
  background-color: white;
  height: 101vh;
  overflow: hidden;
  position: fixed;
  top: 0;
  z-index: 1;
  @include media-breakpoint-down(md) {
    height: 70vh;
  }
  width: 100vw;
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
}
</style>
