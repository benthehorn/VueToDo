<template>
  <div>
    <to-do-list></to-do-list>
  </div>
</template>

<script>
import ToDoList from './components/ToDoList';

export default {
  components: {
    ToDoList,
  },

  data() {
    return {
      todos: [{
        title: 'Todo A',
        project: 'Project A',
        done: false,
      },
      {
        title: 'Todo B',
        project: 'Project B',
        done: true,
      },
      ,
      {
        title: 'Todo D',
        project: 'Project D',
        done: false,
      }],
    };
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
