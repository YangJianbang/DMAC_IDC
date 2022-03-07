<template>
  <div id="app">
    <Test/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Test from "./components/Test";

export default {
  name: 'App',
  components: {
    // HelloWorld,
    Test
  }
}
</script>

<style>
body {
  padding: 0;
  margin:0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
