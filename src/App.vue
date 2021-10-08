<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <highlightjs
      language="javascript"
      code="function chipPaginate(page) {
    if (typeof sortOrderNew === 'undefined')
        var sortOrder = 3;

    if (typeof sortOrderNew !== 'undefined')
        var sortOrder = sortOrderNew;

    console.log(sortOrder);
}
"
    />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld
  }
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
