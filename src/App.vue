<template>
  <div>{{ message }}</div>
  <span :title="message">Hover aku</span>
</template>

<script>

export default {
  data(){
    return {
      message: 'hello world'
    }
  }
}
</script>
