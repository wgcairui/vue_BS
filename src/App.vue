
<template>
  <div id="app">
    <app_header title="休闲乐" src=""></app_header>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import app_header from "./components/head.vue";
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    app_header
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
