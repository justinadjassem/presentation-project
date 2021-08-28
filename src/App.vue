<template>
  <div id="app">
    <Header />
    <side-bar /> 
  </div>
</template>

<script>
import Header from './components/header/header.vue'
import SideBar from './components/sidebar/sidebar.vue'


export default {
  name: 'App',
  components: {
    SideBar,
    Header
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
}
</style>
