<template>
  <div class="signup-page">
    <h1 class="title">Sign Up</h1>
    <form class="signup-form">
      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" id="name" v-model="name" />
      </div>
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" v-model="email" />
      </div>
      <div class="form-group">
        <label for="password">Password</label>
        <input type="password" id="password" v-model="password" />
      </div>
      <button class="signup-button" @click="submitForm">Sign Up</button>
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
    submitForm() {
      // Handle form submission
    },
  },
};
</script>


