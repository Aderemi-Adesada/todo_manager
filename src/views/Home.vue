<template>
  <div class="home">
    <div class="container">
      <AddTodo />
      <FilterTodos />
      <Todos />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Todos from "@/components/Todos.vue";
import AddTodo from "@/components/AddTodo.vue";
import FilterTodos from "@/components/FilterTodos.vue";

export default {
  name: "Home",
  components: {
    Todos,
    AddTodo,
    FilterTodos,
  },
};
</script>

<style lang="scss">
  body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.6;
  background: white;
  .home {
    .container {
      max-width: 1100px;
      margin: auto;
      overflow: auto;
      padding: 0 2rem;
    }
  }
}



</style>
