<template>
  <div id="app">
    <Header />
    <Main />
    <Footer></Footer>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
// import Thumbs from './components/Thumbs.vue';

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style lang="scss">
 @import "./assets/scss/style.scss"

</style>
