<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" width="25%">
    <vue-typed-js :strings="['First text', 'Second Text']" :typeSpeed="50" :loop="true">
      <h1 class="typing"></h1>
    </vue-typed-js>
    <HelloWorld msg="Hello Vue in CodeSandbox!"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
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
.typing {
  margin-left: 18.5rem;
  height: 44px;
}
</style>
