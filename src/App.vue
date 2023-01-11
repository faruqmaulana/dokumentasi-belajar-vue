<template>
  <div>
    Ini adalah parent component
  </div>
  <child-component v-for="todo in todos" :key="todo" :text="todo"/>
</template>

<script>

import ChildComponent from './components/ChildComponent.vue'

export default {
  components: { ChildComponent },
  data(){
    return {
      todos : [ 'pertama', 'kedua', 'ketiga']
    }
  }
}
</script>
