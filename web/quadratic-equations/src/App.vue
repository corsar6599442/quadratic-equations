<template>
  <div id="app">
    <h1> {{ header }} </h1>
    <!-- <HelloWorld msg=""/> -->
    <MyHeader header="An application for solving quadratic equations"/>
    <hr>
    <MyComponent/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import MyHeader from './components/MyHeader.vue'
import MyComponent from './components/MyComponent.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld,
    MyHeader,
    MyComponent
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
