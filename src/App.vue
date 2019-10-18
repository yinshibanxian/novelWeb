<template>
  <div id="app">
    <NavBar />
  </div>
</template>

<script>
import NavBar from './components/NavBar';
export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>

<style>
#app {
  height: 100%;
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background: #E9FAFF;
}
</style>
