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
  background: linear-gradient(-45deg, #FFEEEE, #FFF6EA, #F7E9D7, #EBD8C3);
  background-size: 400% 400%;
  animation: gradient 15s ease infinite;
  height: 100vh;
}

@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
</style>
