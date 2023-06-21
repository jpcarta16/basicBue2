<template>
  <div>
    <h1>User Profile</h1>
    <p>Name: {{ user.name }}</p>
    <p>Email: {{ user.email }}</p>
  </div>
</template>

<script>
export default {
  name: 'UserProfile',
  data() {
    return {
      user: null
    };
  },
  mounted() {
    this.fetchUser();
  },
  methods: {
    fetchUser() {
      setTimeout(() => {
        this.user = {
          name: 'John Doe',
          email: 'johndoe@example.com'
        };
      }, 1000);
    }
  }
};
</script>
