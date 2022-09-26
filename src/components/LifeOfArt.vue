<template>
  <b-container class="lifeofart" id="lifeofart" fluid>
    <b-row class="lifeofart__title">
      <h2 class="mt-5">THE LIFE OF MY ART</h2>
      <h3 class="mt-3">Because I want you to meet them in person</h3>
    </b-row>
    <div class="mt-4">
      <b-card-group columns class="lifeofart__masonry">
        <div class="lifeofart__card">
          <img src="../assets/lifeofart/IMG_5416.jpeg" alt="" class="mt-4 p-2" />
          <img src="../assets/lifeofart/IMG_9687.jpeg" alt="" class="mt-4 p-2" />
          <img src="../assets/lifeofart/IMG_6595.jpeg" alt="" class="mt-4 p-2" />
          <img src="../assets/lifeofart/IMG_6602.jpeg" alt="" class="mt-4 p-2" />
          <img src="../assets/lifeofart/IMG_7157.jpeg" alt="" class="mt-4 p-2" />
          <img src="../assets/lifeofart/IMG_7294.jpeg" alt="" class="mt-4 p-2" />
          <img src="../assets/lifeofart/IMG_8653.jpeg" alt="" class="mt-4 p-2" />
          <img src="../assets/lifeofart/IMG_8696.jpeg" alt="" class="mt-4 p-2" />
        </div>
      </b-card-group>
    </div>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.lifeofart {
  background-color: black;
  color: white;
  @include media-breakpoint-up(md) {
    padding: 0 10%;
  }
  &__title {
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

</style>
