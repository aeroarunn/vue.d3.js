<template>
  <div id="app">
    <Header />
    <Home msg="Hello Vue in CodeSandbox!" />
  </div>
</template>

<script>
import Header from "./components/Header";
import Home from "./components/Home";
export default {
  name: "App",
  components: {
    Home,
    Header,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
