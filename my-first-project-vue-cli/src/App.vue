<template>
  <div id="app">

    <firstComponent/> <!-- USA IL COMPONENTE --> 
    
  </div>
</template>

<script>
  // IMPORTA IL COMPONENTE DA USARE
import firstComponent from './components/AppTitle.vue'

export default {
  name: 'App',
  components: {
    firstComponent // IMPORTANTE: DICHIARA IL COMPONENTE DA USARE
  }
}
</script>

<style lang="scss">
  /* CSS GENERALE */
#app {
  background-color: black;
}
body {
  background-color: grey;
}
</style>
