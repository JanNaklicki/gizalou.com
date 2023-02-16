<template>
  <b-navbar toggleable="lg" type="dark" variant="dark" style="z-index: 10">
    <b-navbar-toggle target="nav-collapse" class="ml-auto"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto h4 p-3">
        <b-nav-item href="#gallery">GALLERY</b-nav-item>
        <b-nav-item href="#products">PRODUCTS</b-nav-item>
        <b-nav-item href="#about">ABOUT ME</b-nav-item>
        <b-nav-item href="#contact">CONTACT</b-nav-item>
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
  font-size: 1.2rem;
  letter-spacing: 1px;
  font-family: "Amatic SC", cursive;
  font-family: "Montserrat", sans-serif;
  &:hover {
    color: #fc1d72 !important;
  }
}
.navbar {
  background-color: black !important;
  border: none;
  @include media-breakpoint-up(sm) {
    background-color: rgba(218, 0, 84, 0) !important;
  }
}

.navbar-toggler {
  border: none;
  font-size: 1.6rem;
}
</style>
