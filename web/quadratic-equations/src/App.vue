<template>
  <div id="app">
    <h1> {{ header }} </h1>
    <HelloWorld msg=""/>
    <MainApp message="Привет"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MainApp from './components/MainApp.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MainApp,
  },
  Date: {
    header: 'Привет лунатикам!'
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #6c947e;
  margin-top: 60px;
}
</style>
