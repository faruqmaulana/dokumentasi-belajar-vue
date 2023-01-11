<template>
  <div>{{ count }}</div>
  <button @click="addCount" :disabled="count >= 10">Add 1</button>
  <button @click="reduceCount" :disabled="count <= 0">min 1</button>
</template>

<script>
export default {
  data(){
    return {
      message: 'Hello World',
      count: 0
    }
  },
  methods:{
    addCount(){
      this.count++
    } ,
    reduceCount(){
      this.count--
    } 
  }  

}
</script>
