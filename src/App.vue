<template>
  <div id="app">
    <Navigation />
    <Home />
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import Home from "./components/Home.vue";

export default {
  name: "app",
  components: {
    Navigation, Home
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Ubuntu:400,700');

#app {
font-family: 'Ubuntu', sans-serif;
}
</style>
