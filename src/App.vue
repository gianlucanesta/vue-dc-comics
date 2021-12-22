<template>
  <div id="app">
    <Header :links="links" />

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
  data: function() {
        return {
            links: [
                {
                    text: 'characters',
                    url: '#',
                    current: false
                },
                {
                    text: 'comics',
                    url: '#',
                    current: true
                },
                {
                    text: 'movies',
                    url: '#',
                    current: false
                },
                {
                    text: 'tv',
                    url: '#',
                    current: false
                },
                {
                    text: 'games',
                    url: '#',
                    current: false
                },
                {
                    text: 'collectibles',
                    url: '#',
                    current: false
                },
                {
                    text: 'videos',
                    url: '#',
                    current: false
                },
                {
                    text: 'fans',
                    url: '#',
                    current: false
                },
                {
                    text: 'news',
                    url: '#',
                    current: false
                },
                {
                    text: 'shop',
                    url: '#',
                    current: false
                }
            ]
        }
  }
};
</script>

<style lang="scss">
@import './style/general.scss';
@import './style/common.scss';
@import './style/variables.scss';

</style>
