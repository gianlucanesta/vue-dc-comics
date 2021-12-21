<template>
  <div id="app">
    <Header />

    <Main />

    <Icons />

  
    <Footer />
    
  
  
  </div>
</template>

<script>
//import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Icons from "./components/Icons.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Icons,
    Footer,
  },
};
</script>

<style lang="scss">
@import './style/general.scss';
@import './style/common.scss';
@import './style/variables.scss';

</style>
