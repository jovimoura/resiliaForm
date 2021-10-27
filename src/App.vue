<template>
  <Header />
  <Principal />
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Principal from './components/Principal/Principal.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Principal,
    Footer
  }
}
</script>

<style>
  body {
    margin:0;
    
  }
</style>
