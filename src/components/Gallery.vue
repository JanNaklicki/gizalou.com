<template>
  <div class="gallery">
    <b-row>
      <b-col class="gallery__item" sm="12" xl="4">
        <img src="../assets/art1.png" alt="" />
      </b-col>
      <b-col class="gallery__item" sm="12" xl="4">
        <img src="../assets/art2.png" alt="" />
      </b-col>
      <b-col class="gallery__item" sm="12" xl="4">
        <img src="../assets/art3.png" alt="" />
      </b-col>
    </b-row>
    <b-row>
      <b-col class="gallery__item" sm="12" xl="4">
        <img src="../assets/art4.png" alt="" />
      </b-col>
      <b-col class="gallery__item" sm="12" xl="4">
        <img src="../assets/art5.png" alt="" />
      </b-col>
      <b-col class="gallery__item" sm="12" xl="4">
        <img src="../assets/art6.png" alt="" />
      </b-col>
    </b-row>
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
    // padding: 50px;

    img {
      width: 100%;
    }
  }
}
.row {
  margin-bottom: 30px;
}
</style>
