<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
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

<style>
</style>
