<template>
  <div id="app">

  </div>
</template>

<script>
  import firework from './components/firework'

export default {
  name: 'app',
  created(){
      firework.show()
  },
  components: {

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
