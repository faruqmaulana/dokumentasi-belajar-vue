<template>
  Ini adalah parent component
  <ChildComponent/>
</template>

<script>

import ChildComponent from './components/ChildComponent.vue'

export default {
  components: { ChildComponent }
}
</script>
