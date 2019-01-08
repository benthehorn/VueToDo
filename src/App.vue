<template>
  <div>
    <to-do-list></to-do-list>
  </div>
</template>

<script>
import ToDoList from './components/ToDoList'

export default {
  components: {
    ToDoList,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
