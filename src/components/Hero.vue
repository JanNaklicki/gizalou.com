<template>
  <div class="hero">
    <video
      autoplay
      muted
      loop
      style="
        width: 70%;
        max-width: 70%;
        height: auto;
        margin-left: auto;
        margin-right: auto;
      "
    >
      <source src="../assets/background.mp4" type="video/mp4" />
    </video>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.hero {
  height: 130vh;
  overflow: hidden;
  margin-top: -18%;
  z-index: 10;
  video {
    width: 100%;
    z-index: 25;
  }
}
</style>
