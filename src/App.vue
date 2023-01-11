<template>
  <div v-if="status">Ini tampil</div>
  <button @click="setStatus">toogle</button>
  <div v-if="status">true</div>
  <div v-else-if="status2">false</div>
  <div v-else>arrrghh</div>
</template>

<script>

export default {
  data() {
    return {
      status: false,
      status2: true
    }
  },
  methods: {
    setStatus(){
      this.status = !this.status
    }
  }
}
</script>
