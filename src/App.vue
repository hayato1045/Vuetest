<template>
  <div id="app" class="container">
    <img class="logo" alt="Vue logo" src="./assets/logo.png" />
    <todo-list></todo-list>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import TodoList from "./components/TodoList.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    TodoList
  }
};
</script>

<style lang="scss">
.container {
  max-width: 600px;
  margin: 0 auto;
}
#app {
  color: #2c3e50;
  margin-top: 60px;
  font-size: 24px;
}
.logo {
  display: block;
  margin: 20px auto;
  height: 75px;
}
</style>
