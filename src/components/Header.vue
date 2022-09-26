<template>
  <b-navbar toggleable="lg" type="dark" variant="dark" style="z-index: 10">
    <b-navbar-toggle target="nav-collapse" class="ml-auto"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto h4 p-3">
        <b-nav-item href="#gallery">Gallery</b-nav-item>
        <b-nav-item href="#products">Products</b-nav-item>
        <b-nav-item href="#about">About me</b-nav-item>
        <b-nav-item href="#contact">Contact</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped lang="scss">
.nav-link {
  color: #da0053 !important;
  font-family: "Amatic SC", cursive;
  font-family: "Montserrat", sans-serif;
  &:hover {
    color: #fc1d72 !important;
  }
}
.navbar {
  background-color: black!important;
  @include media-breakpoint-up(sm) {
    background-color: rgba(218, 0, 84, 0) !important;
  }
}
</style>
