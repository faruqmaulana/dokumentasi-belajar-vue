<template>
  <ol>
    <li v-for="(todo, index) in todos" :key="todo.id">
      {{ index }} {{ todo.activity }}
    </li>
  </ol>
</template>

<script>

export default {
  data() {
    return {
      todos:[
        { id:1, activity: 'menyapu' }, 
        { id:2, activity: 'minum' },
        { id:3, activity: 'menyapa' } 
      ]
    }
  }
}
</script>
