<template>
  <div id="app">
    <div class="container">
      <AddTodo />
      <FilterTodo />
      <Todos />
    </div>
  </div>
</template>

<script>
import AddTodo from "./components/AddTodo";
  import Todos from "./components/Todos.vue";
  import FilterTodo from "./components/FilterTodo";

export default {
  name: 'app',
  components: {
    AddTodo,
    Todos,
    FilterTodo
  }
}
</script>

<style>

body{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container{
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
