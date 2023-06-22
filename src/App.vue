<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
import Home from './views/Home.vue';
import { RouterLink, RouterView } from 'vue-router'

export default {
  components: {
    Home,
  },
};
</script>

<style>
#app {
  margin: 0 auto;

}
</style>
