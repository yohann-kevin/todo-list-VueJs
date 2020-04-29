<template>
  <div id="app">
    <todos/>
    <!-- <todos />
    <todos />
    <button @click="addTodo()">Ajouter une tâche</button> -->
  </div>
</template>

<script>
import Todos from './components/Todos'

export default {
  name: 'App',
  data () {
    return {
      todos: [{
        name: 'Demo',
        completed: true
      }]
    }
  },
  components: {
    Todos
  },
  // methods: {

  //   addTodo () {
  //     this.todos.push({
  //       name: 'jean',
  //       completed: false
  //     })
  //   }
  // }
}
</script>


