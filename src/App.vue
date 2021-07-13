<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Main :comics="comics" />
    <SectionBlu />
    <Footer />
  </div>
</template>

<script>
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
import SectionBlu from './components/SectionBlu.vue';
import Main from './components/Main.vue';
import comicsJson from './jsons/dc-comics.json';
import Jumbotron from './components/Jumbotron.vue';


export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Main,
    SectionBlu,
    Footer
  },
  data: function() {
    return {
      comics: comicsJson,
    };
  },
};
</script>

<style lang="scss">
@import './style/app.scss';
</style>
