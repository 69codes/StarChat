<template>
    <div>
      <h1>Sign Up</h1>
      <form>
        <div>
          <label for="name">Name:</label>
          <input type="text" id="name" v-model="name" placeholder="Enter your name">
        </div>
        <div>
          <label for="email">Email:</label>
          <input type="email" id="email" v-model="email" placeholder="Enter your email">
        </div>
        <div>
          <label for="password">Password:</label>
          <input type="password" id="password" v-model="password" placeholder="Enter your password">
        </div>
        <button @click="submit">Sign Up</button>
      </form>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        name: '',
        email: '',
        password: '',
      };
    },
    methods: {
      submit() {
        // Perform sign-up logic here
        console.log('Name:', this.name);
        console.log('Email:', this.email);
        console.log('Password:', this.password);
      },
    },
  };
  </script>
  
  <style scoped>
  h1 {
    color: #333;
  }
  form {
    margin-top: 20px;
  }
  div {
    margin-bottom: 10px;
  }
  label {
    display: block;
    font-weight: bold;
  }
  input {
    width: 100%;
    padding: 5px;
    border: 1px solid #ccc;
    border-radius: 3px;
  }
  button {
    padding: 8px 16px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 3px;
    cursor: pointer;
  }
  </style>
  