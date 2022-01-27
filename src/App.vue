<template>
  <div id="app">
    <header-box />
    <jumbotron-box />
    <main-container />
    <footer-merch />
    <footer-contacts />
    <footer-social />
  </div>
</template>

<script>
import FooterContacts from "./components/FooterContacts.vue";
import FooterMerch from "./components/FooterMerch.vue";
import HeaderBox from "./components/HeaderBox.vue";
import JumbotronBox from "./components/JumbotronBox.vue";
import MainContainer from "./components/MainContainer.vue";
import FooterSocial from "./components/FooterSocial.vue";

export default {
  name: "App",
  components: {
    HeaderBox,
    JumbotronBox,
    MainContainer,
    FooterMerch,
    FooterContacts,
    FooterSocial,
  },
};
</script>

<style lang="scss">
@import "./style/main.scss";
</style>
