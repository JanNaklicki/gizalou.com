<template>
  <div class="gallery">
    <b-container>
      <b-row> ÷ </b-row>
    </b-container>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
.cell {
  background-color: white;
}
.gallery {
  margin: 0 auto;
  padding: 0 30px;
  width: 100%;
  // background-color: #8d67ca;

  &__item {
    display: flex;
    justify-content: center;
    margin-bottom: 30px;

    // padding: 50px;

    img {
      width: 100%;
    }
  }
}
.row {
}
</style>
