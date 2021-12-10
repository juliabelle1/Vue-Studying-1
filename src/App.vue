<template>
 <div>
   <appNavbar />
   <Hero />
   <Footer />
 </div>
</template>

<script>

import Navbar from './components/navigation/Navbar.vue'
import Hero from './components/hero/Hero.vue'
import Footer from './components/Footer/Footer.vue'

export default {
  name: 'App',
  components: {
    appNavbar: Navbar,
    Hero,
    Footer
  }
}
</script>

<style>

</style>