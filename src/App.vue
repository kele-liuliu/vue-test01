<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />

    <B />
    <A />
  </div>
</template>

<script>
import A from "./components/a.vue";
import B from "./components/b";
export default {
  name: "App",
  components: { B, A },
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
