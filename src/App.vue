<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Hello world."/> -->
    <test1 isMorning=false />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import test1 from './components/test1.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld
    test1
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
