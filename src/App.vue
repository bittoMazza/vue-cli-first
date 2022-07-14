<template>
  <div id="app">
    <TitleHeader/>
    <HeroHeader/>
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
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body{
  background-color:antiquewhite;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
