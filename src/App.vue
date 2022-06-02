<template>
  <Menu msg="Purz"/>
  <Holograms msg="Purz's Holograms"/>
</template>

<script>
import Menu from './components/Menu.vue'
import Holograms from './components/Holograms.vue'

export default {
  name: 'App',
  components: {
    Menu,
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
  color: #000000;
}

body {
  background: #ffffff;
  margin: 0px;
}
.rainbowBG {
  background: linear-gradient(-45deg, #F08080, #F4978E, #F8AD9D, #FFDAB9);
  background-size: 400% 400%;
  animation: gradient 12s ease infinite;
  height: 100%;
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
