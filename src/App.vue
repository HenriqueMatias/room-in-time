<template>
  <div id="app">
    <navbar></navbar>
    <hello></hello>
  </div>
</template>

<script>
import Hello from './components/Hello'
import navbar from './components/NavBar'

export default {
  name: 'app',
  components: {
    navbar,
    Hello
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
}
</style>
