<template>
  <div id="app" class = "container">
    <div>
      <TodoNew />
      <TodoList />
      <img alt="Vue logo" src="./assets/logo.png" />
    </div>
  </div>
</template>

<script>
import TodoNew from "@/components/TodoNew.vue";
import TodoList from "@/components/TodoList.vue";

export default {
  name: "app",
  components: {
    TodoNew,
    TodoList
  }
};
</script>

<style lang="less">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

html {
  font-family: "Open Sans", sans-serif;
  background: linear-gradient(45deg, #5189c1 25%, #41b883);
  height: 100%;
  color: #333;
}

body {
  display: flex;
  height: 100%;
  margin: 0;
}

.container {
  width: 24rem;
  margin: auto;
  background-color: white;
  border-radius: 1rem;
  padding: 1rem;
  box-shadow: 0 0 1rem rgba(0, 0, 0, 0.5);
}

h1 {
  text-align: center;
  margin-top: 0;
}

.vue-logo {
  display: block;
  width: 50px;
  margin: 0 auto;
}
</style>
