<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Pirates :pirates="pirates"/>
  </div>
</template>

<script>
import pirates from './pirates.js';
import Pirates from './components/Pirates.vue';

export default {
  data() {
    return { pirates };
  },
  name: 'app',
  components: {
    Pirates
  }
};
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
