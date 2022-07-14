<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleHeader/>
    <hero-header/>
  </div>
</template>

<script>
import HeroHeader from './components/Hero.vue'
import TitleHeader from './components/Title.vue'

export default {
  name: 'App',
  components: {
    TitleHeader,
    HeroHeader,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
