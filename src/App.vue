<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
import Home from './views/Home.vue';

export default {
  components: {
    Home,
  },
};
</script>

<style>
#app {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
}
</style>
