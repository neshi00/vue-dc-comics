<template>
  <div id="app">
    <header-box />
    <jumbotron-box />
    <main-container />
    <footer-merch />
  </div>
</template>

<script>
import FooterMerch from "./components/FooterMerch.vue";
import HeaderBox from "./components/HeaderBox.vue";
import JumbotronBox from "./components/JumbotronBox.vue";
import MainContainer from "./components/MainContainer.vue";

export default {
  name: "App",
  components: {
    HeaderBox,
    JumbotronBox,
    MainContainer,
    FooterMerch,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");
@import "./style/main.scss";
</style>
