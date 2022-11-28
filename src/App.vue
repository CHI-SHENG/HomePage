<template>
  <v-app>
    <Header/>
    <v-main>
      <HeroComponents/>
      <About/>
      <Portfolio/>
      <Project/>
      <Gallery/>
      <Contactus/>
      <Footer/>
    </v-main>
  </v-app>
</template>

<script>
import Header from "./components/Header"
import HeroComponents from "./components/HeroComponents"
import About from "./components/About.vue"
import Portfolio from "./components/Portfolio"
import Project from "./components/Project"
import Gallery from "./components/Gallery"
import Contactus from "./components/Contactus"
import Footer from "./components/Footer"

export default {
  name: 'App',
  components:{
    Header,
    HeroComponents,
    About,
    Portfolio,
    Project,
    Gallery,
    Contactus,
    Footer
  }

};
</script>
