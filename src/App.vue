<template>
  <Header/>
  <Banner/>
  <Projects />
  <CV />
  <Contact />
  <Footer />
</template>

<script>
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import Contact from "./components/Contact.vue";
import CV from "./components/CV.vue";
import Footer from "./components/Footer.vue";
import Projects from "./components/Projects.vue";

export default {
  name: "App",
  components: {
    Header,
    Banner,
    Contact,
    CV,
    Footer,
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
