<template>
  <Holograms msg="Purz's Holograms"/>
</template>

<script>
import Holograms from './components/Holograms.vue'

export default {
  name: 'App',
  components: {
    Holograms
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  background: linear-gradient(to bottom, lightgray , gray);
}
</style>
