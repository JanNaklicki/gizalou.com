<template>
  <header class="header">
    <div>strona główna</div>
    <div>portfolio</div>
    <div>o mnie</div>
    <div>kontakt</div>
  </header>
  <main>
    <video
      autoplay
      muted
      loop
      id="myVideo"
      style="
        width: 70%;
        max-width: 70%;
        height: auto;
        margin-left: auto;
        margin-right: auto;
      "
    >
      <source src="./assets/background.mp4" type="video/mp4" />
    </video>
  </main>
  <footer></footer>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
  background-color: #040007;
}
.header {
  padding: 20px;
  padding-top: 40px;
  display: flex;
  justify-content: flex-end;
  font-size: 35px;
  font-family: "Josefin Sans", sans-serif;
  position: sticky;
  z-index: 10;
}
.header div {
  margin-right: 20px;
  color: #2f05bc;
}
.header div:hover {
  color: #db015c;
}
main {
  height: 130vh;
  overflow: hidden;
  margin-top: -18%;
}
main video {
  width: 100%;
}
</style>
