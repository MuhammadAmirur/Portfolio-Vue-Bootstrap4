<template>
  <div id="app">
    <WebsiteBootstrap />
  </div>
</template>

<script>
import WebsiteBootstrap from "./components/WebsiteBootstrap.vue";

export default {
  components: {
    WebsiteBootstrap,
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
}
</style>
