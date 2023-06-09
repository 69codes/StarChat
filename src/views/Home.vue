<template>
    <div class="home">
      <Header />
      <div class="spacer"></div>
      <SignUp />
    </div>
  </template>
  
  <script>
  import Header from '../components/Header.vue';
  import SignUp from '../components/SignUp.vue';
  
  export default {
    components: {
      Header,
      SignUp,
    },
  };
  </script>
  
  <style scoped>
  .home {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
  }
  
  .spacer {
    height: 50px;
  }
  
  @media (min-width: 768px) {
    /* Adjust the layout for larger screens */
    .home {
      flex-direction: row;
      justify-content: center;
    }
  
    .spacer {
      width: 50px;
      height: auto;
    }
  }
  </style>
  