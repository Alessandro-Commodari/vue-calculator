<template>
  <div id="app">
    <img src="./assets/logo.png" />
    <h1>Inspired by the Microsoft Standard Calculator</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./components/Calculator.vue";

export default {
  name: "App",
  components: {
    Calculator
  }
};
</script>

<style>
body {
  background-color: #43484d;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #eaeef2;
  margin-top: 4.25rem;
}

img {
  max-width: 3rem;
}

h1 {
  font-size: 2rem;
  text-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.3);
}
</style>
