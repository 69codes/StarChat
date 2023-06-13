<template>
    <div class="home">
      <Header />
      <div class="hero"> Chat with your favorite celebrities</div>
    </div>
  </template>
  
  <script>
  import Header from '../components/Header.vue';
  
  export default {
    components: {
      Header,
    },
  };
  </script>
  
  <style scoped> 
  .hero {
    font-size: xx-large;
    color: blue;
    margin-top: 20px 20px;
  }

  </style>
  