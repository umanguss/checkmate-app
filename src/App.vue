<template>
   <div id="app">
      <todo-app></todo-app>
   </div>
</template>

<script>
import TodoApp from './components/TodoApp.vue'

export default {
  name: 'App',
  components: {
    TodoApp
  }
}
</script >
<style>
#app{
  background-image: url("./assets/todoimage.jpg");
  height: 130vh;
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  margin: -50px;
}
</style>