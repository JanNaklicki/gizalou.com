<template>
  <b-container fluid class="gallery">
    <b-row class="gallery__title">
      <h2 class="mt-5">GALLERY</h2>
      <h3 class="mt-3">Because every good mama makes an album of her babies</h3>
    </b-row>
    <b-card-group columns class="gallery__masonry">
      <div class="gallery__card">
        <img src="../assets/1-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/0-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/2-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/3-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/4-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/5-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/6-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/7-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/8-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/9-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/10-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/11-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/12-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/13-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/14-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/15-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/16-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/17-thubnail.png" alt="" class="mt-4 p-2" />
        <img src="../assets/18-thubnail.png" alt="" class="mt-4 p-2" />
      </div>
    </b-card-group>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss">
.gallery {
  position: relative;
  z-index: 2;
  background-color: #000;
  &__title {
    color: rgb(233, 233, 233);
    display: flex;
    flex-direction: column;
    align-content: center;
    text-align: center;
    padding: 0 15px;
    h2 {
      text-align: center;
      letter-spacing: 6px;
      font-size: 2.8rem;
      font-weight: 600;
    }
    h3 {
      font-size: 1.2rem;
      font-weight: normal;
    }
  }
  &__masonry {
    padding: 50px 10%;
  }
  &__card {
    img {
      width: 100%;
      transition: transform 0.3s;
      transition-timing-function: cubic-bezier(0.06, 0.24, 0.25, 1);

      &:hover {
        transform: scale(1.08);
        @include media-breakpoint-down(md) {
          transform: scale(1.02);
        }
      }
    }
  }
}

@include media-breakpoint-up(xl) {
  .card-columns {
    column-count: 4 !important;
  }
}
</style>
