<template>
    <div class="home">
      <Header />
      <!--The whole page would be in a flex container-->
      <div class="Flex_container"> 
        <div class="flex_one">

        </div>
        <div class="flex_two">

        </div>
        <div class="flex_three">


        </div>
       
      </div>
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


  /* All the flex containers would be inside this one */
  .Flex_container {
    display: flex;
    flex-direction: column;
  }

  /* We would be having three main flex containers in the flex containers, which would dictate the whole page */
  .flex_one {
    height: 150px;
    background-color: aqua;
  }

  .flex_two {
    height: 150px;
    background-color: red;
  }

  .flex_three {
    height: 150px;
    background-color: burlywood;
  }
  </style>
  