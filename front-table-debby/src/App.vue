<template>
  <div id="app">
    <Header/>
    <Home/>
    <Menu/>
    <Place/>
    <Team/>
    <Food/>
    <About/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Food from './components/Food.vue'
import Footer from './components/Footer.vue'
import Menu from './components/Menu.vue'
import Place from './components/Place.vue'
import Team from './components/Team.vue'

export default {
  name: 'App',
  components: {
    Header,
    Home,
    About,
    Food,
    Footer,
    Menu,
    Place,
    Team,
  }
}
</script>

<style lang="scss">

</style>
