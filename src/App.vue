<template>
  <Home msg="Welcome to Your Vue.js App"/>
</template>

<script>
import Home from './components/HomeComponent.vue';

export default {
  name: 'App',
  components: {
    Home,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: white;
}
body {
  background: black;
}
</style>
