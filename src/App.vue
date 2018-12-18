<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
    <vue1/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import vue1 from './components/vue1'

export default {
  name: 'App',
  components: {
    HelloWorld,vue1
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
