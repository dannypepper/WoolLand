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
  data: () => ({
    products: [
      {
        name: 'Phone case',
        cost: '5000 HUF',
        image: '../assets/image/lila_tok.jpg',
      },
    ],
  }),
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: white;
  /* padding: 0;
  margin: 0; */
}
body {
  background: black;
}
</style>
