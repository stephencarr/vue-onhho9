<template>
  <div id="app">
    <NavBar />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import 'nes.css/css/nes.min.css';

export default {
  name: 'App',
  components: {
    NavBar,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
</style>
