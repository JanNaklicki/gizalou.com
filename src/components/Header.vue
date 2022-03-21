<template>
  <header class="header">
    <nav>
      <div>strona główna</div>
      <div>portfolio</div>
      <div>o mnie</div>
      <div>kontakt</div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped lang="scss">
.header {
  padding: 20px;
  padding-top: 40px;
  font-size: 35px;
  font-family: "Josefin Sans", sans-serif;
  position: sticky;
  z-index: 10;
  nav {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
  }
  div {
    margin-right: 20px;
    color: #2f05bc;
  }
  div:hover {
    color: #db015c;
  }
}
</style>
