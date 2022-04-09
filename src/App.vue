<template>
  <div>
    <NavBar class="fixed z-50 w-full"/>
    <HeroSection />
    <AboutSection />
    <ServiceSection />
    <ServiceSection2 />
    <CallToAction />
    <FooterSection1 /> 
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import HeroSection from './components/HeroSection.vue'
import AboutSection from './components/AboutSection.vue'
import ServiceSection from './components/ServiceSection.vue'
import ServiceSection2 from './components/ServiceSection2.vue'
import CallToAction from './components/CallToAction.vue'
import FooterSection1 from './components/FooterSection1.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    HeroSection,
    AboutSection,
    ServiceSection,
    ServiceSection2,
    CallToAction,
    FooterSection1,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
