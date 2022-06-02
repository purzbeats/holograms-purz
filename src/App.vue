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
  margin-top: 60px;
}

body {
  background: #ffffff;
  margin: 0px;
}
.rainbowBG {
  background: linear-gradient(-45deg, #F2789F, #F999B7, #F9C5D5, #FEE3EC);
  background-size: 200% 200%;
  animation: gradient 30s ease infinite;
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
