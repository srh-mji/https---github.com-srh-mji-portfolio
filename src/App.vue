<template>
  <Header/>
  <Banner/>
  <Projects />
  <CV />
  <Contact />
</template>

<script>
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import Contact from "./components/Contact.vue";
import CV from "./components/CV.vue";
import Projects from "./components/Projects.vue";

export default {
  name: "App",
  components: {
    Header,
    Banner,
    Contact,
    CV,
    Projects
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
