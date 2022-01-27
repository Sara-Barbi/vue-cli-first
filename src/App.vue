<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld/>
    <titolo/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import titolo from './components/titolo.vue'       


export default {
  name: 'App',
  components: {
    HelloWorld,
    titolo,
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
  margin-top: 60px;
}
</style>
