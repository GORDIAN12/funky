<template>
  <div id="app">
    <img alt="Vue logo" src="https://i.pinimg.com/originals/df/01/58/df01585fa683de25ae8f1a0be7003162.png">
    <HelloWorld msg="welcome "/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
