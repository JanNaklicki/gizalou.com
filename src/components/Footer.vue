<template>
  <b-container id="contact" fluid class="footer">
    <b-container>
      <b-row class="p-4 pt-5">
        <b-col class="h1" cols="5" sm="6"> LET'S TALK </b-col>
        <b-col>
          <p><b class="h4">Julia Giza</b></p>
          <p><b-icon-instagram/> <a href="https://www.instagram.com/giza.lou/"> @giza.lou</a></p>
          <p><b-icon-telephone/> <a href="tel:+48 502 625 276">+48 502 625 276</a></p>
        </b-col>
      </b-row>
    </b-container>
  </b-container>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.footer {
  color: white;
  background-color: black;
  a {
    color: #df0160;
    text-decoration: none;

    &:visited {
      color: #fc1d72;
      text-decoration: none;
    }
    &:hover {
      opacity: 0.7;
      text-decoration: none;
    }
    &:active {
      opacity: 1;
      text-decoration: none;
    }
  }
}
</style>
