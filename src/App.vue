<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MyTitle />
    <NewHero />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyTitle from './components/MyTitle.vue'
import NewHero from './components/NewHero.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyTitle,
    NewHero,
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
