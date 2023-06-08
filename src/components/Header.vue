<template>
    <header>
      <nav>
        <div class="left">
          <router-link to="/">Home</router-link>
        </div>
        <div class="middle">
          <router-link to="/pricing">Pricing</router-link>
          <router-link to="/contact">Contact</router-link>
        </div>
        <div class="right">
          <router-link to="/about">About</router-link>
        </div>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    name: 'Header',
  };
  </script>
  
  <style scoped>
  header {
    background-color: #f2f2f2;
    padding: 10px;
  }
  
  nav {
    display: flex;
    justify-content: space-between;
  }
  
  .left,
  .right {
    flex-grow: 1;
    text-align: left;
  }
  
  .middle {
    flex-grow: 2;
    text-align: center;
  }
  
  nav a {
    margin: 0 10px;
    text-decoration: none;
    color: #333;
  }
  </style>
  