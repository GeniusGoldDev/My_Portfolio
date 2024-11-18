<template>
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/projects">Projects</router-link>
      <router-link to="/contact">Contact</router-link>
    </nav>
  </template>
  
  <script>
export default {
  name: 'NavbarComponent',
};
</script>
  
  <style scoped>
  nav {
    display: flex;
    justify-content: space-around;
    background-color: #333;
    padding: 1rem;
  }
  nav a {
    color: white;
    text-decoration: none;
  }
  </style>
  