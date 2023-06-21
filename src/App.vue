<template>
  <div id="app">
    <router-link to="/">Home</router-link>
    <router-link to="/user">User Profile</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
};
</script>
