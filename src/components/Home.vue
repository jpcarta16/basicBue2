<template>
  <div>
    <h1>Welcome to the Home Page!</h1>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  name: 'HomePage', 
  data() {
    return {
      message: 'This is the home page of our application.'
    };
  }
};
</script>
