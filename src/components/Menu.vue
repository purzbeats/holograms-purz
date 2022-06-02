<template>
  <div class="hello">
    
  Menu

  </div>
</template>

<script>
export default {
  name: 'Menu',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.portrait {
  width: 400px; 
  min-height: 65vh;
}
.wide {
  width: 100%;
  height: 95vh;
}
</style>
