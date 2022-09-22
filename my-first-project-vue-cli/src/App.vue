<template>
  <div id="app">
    <firstComponent/>
    
  </div>
</template>

<script>
import firstComponent from './components/AppTitle.vue'

export default {
  name: 'App',
  components: {
    firstComponent
  }
}
</script>

<style lang="scss">
#app {
  background-color: black;
}
</style>
