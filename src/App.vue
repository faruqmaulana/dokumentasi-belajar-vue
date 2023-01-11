<template>
  Ini adalah parent component
  <child-component text="Halo 123"/>
  <child-component :text="message"/>
</template>

<script>

import ChildComponent from './components/ChildComponent.vue'

export default {
  components: { ChildComponent },
  data(){
    return {
      message: 'Halo bro'
    }
  }
}
</script>
