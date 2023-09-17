<template>
  <div id="main_app">
    <Navbar />
    <NavBody />
    <InfoBody />
    <Main />
    <Team />
    <Reviews />
    <PreFooter />
    <Footer />
  </div>
</template>

<script setup>
import Navbar from "./components/NavbarComponent.vue";
import NavBody from "./components/NavBodyComponent.vue";
import InfoBody from "./components/InfoComponent.vue";
import Main from "./components/MainComponent.vue";
import Team from "./components/TeamComponent.vue";
import Reviews from "./components/ReviewsComponent.vue";
import PreFooter from "./components/PreFooter.vue";
import Footer from "./components/FooterComponent.vue";
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Gelasio&family=Libre+Franklin:wght@300;400;500;700;800;900&family=Montserrat:wght@400;500&family=Ribeye&family=Roboto+Slab&family=Roboto:wght@300;400&family=Rubik:wght@300;400&family=Source+Serif+4:opsz,wght@8..60,300&family=Tenor+Sans&family=Vollkorn&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Gelasio&family=Libre+Franklin:wght@300;400;500;700;800;900&family=Montserrat&family=Ribeye&family=Roboto+Slab&family=Roboto:wght@300;400&family=Rubik:wght@300;400&family=Source+Serif+4:opsz,wght@8..60,300&family=Tenor+Sans&family=Vollkorn&display=swap");
* {
  list-style: none;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  box-sizing: border-box;
  text-decoration: none;
  padding: 0;
  margin: 0;
  scroll-behavior: smooth;
}
.main_app {
  display: flex;
  justify-content: center;
  margin-left: auto;
  margin-right: auto;
}
</style>
