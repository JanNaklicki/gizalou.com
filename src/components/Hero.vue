<template>
  <div class="hero p-0">
    <b-container fluid class="p-0 hero__container">
      <div class="hero__title">
        <h1 class="h1">@GIZA<span style="color: #df0160">LOU</span></h1>
        <h2 class="h6">JUST MAKIN' THINGS ARTSY</h2>
      </div>
      <img src="../assets/ilonka2.gif" alt="" />
    </b-container>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.hero {
  width: 100vw;
  height: 101vh;
  overflow: hidden;
  position: fixed;
  top: 0;
  background-color: #030007;
  z-index: 1;
  @include media-breakpoint-down(md) {
    display: flex;
    justify-content: center;
  }
  img {
    width: 80%;
    height: 100%;
    object-fit: cover;
    position: fixed;
    top: 0;
    @include media-breakpoint-down(md) {
      width: 100%;
      height: 100%;
    }
  }
  &__container {
    display: flex;
    justify-content: center;
  }
  &__title {
    color: white;
    top: 65vh;
    left: 10vw;
    z-index: 3;
    position: fixed;
    h1 {
      font-size: 4rem;
    }
    @include media-breakpoint-down(md) {
      h1 {
      font-size: 2.5rem;
    }
      top: 80vh;
      left: auto;
    }
  }
  &__arrow {
    font-size: 10px;
    display: flex;
    align-content: center;
    justify-content: center;
    flex-direction: column;
  }
}
</style>
