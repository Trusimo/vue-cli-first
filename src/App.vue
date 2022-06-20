<template>
  <div id="app">
    
    <IlMioTitolo msg="La mia prima app con Vue CLI!"/>
  </div>
</template>

<script>
import IlMioTitolo from './components/IlMioTitolo.vue'

export default {
  name: 'App',
  components: {
    IlMioTitolo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
