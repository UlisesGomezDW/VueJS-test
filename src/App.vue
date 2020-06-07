<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <HelloWorld msg="Hello Vue!"/>
    <DevTest data="Ulises G"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import DevTest from "./components/DevTest";
export default {
  name: "App",
  components: {
    HelloWorld,
    DevTest 
  }
};
</script>

<style>
body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: gray;
  width: 100vw;
  height: 100vh;
}
</style>
