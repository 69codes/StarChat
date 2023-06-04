<template>
  <div id="app">
    <SignUp />
  </div>
</template>

<script>
import SignUp from './components/SignUp.vue';

export default {
  components: {
    SignUp,
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
