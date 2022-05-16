<template>
  <div id="app">
    <AppTitle />
    <Image/>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import AppTitle from './components/AppTitle.vue';
import Image from './components/Image.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    AppTitle,
    Image
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
