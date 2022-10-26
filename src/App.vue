<template>
  <Home page="Vuejs" />
</template>

<script>
// Single-File Component

// Options API
import Home from "./pages/Home";

export default {
  name: "App",
  components: {
    Home: Home,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
