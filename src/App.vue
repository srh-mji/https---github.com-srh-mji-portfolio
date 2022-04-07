<template>
  <Home />
  <Header/>
  <Banner/>
</template>

<script>
import Home from "./components/Home.vue";
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";

export default {
  name: "App",
  components: {
    Home,    
    Header,
    Banner,

  },
};
</script>

<style>
#app {
  font-family: 'Roboto',Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
