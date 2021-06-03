<template>
  
  <navbar/>
  <corpo/>
  <contato/>
  <mapa/>
</template>

<script>
import corpo from './components/corpo.vue'
import navbar from './components/navbar.vue'
import contato from './components/contato.vue'
import mapa from './components/mapa.vue'

export default {
  name: 'App',
  components: {
    corpo,
    navbar,
    contato,
    mapa
  }
}
</script>

<style>
*{
  box-sizing: border-box;
}
html, body{
  padding: 0;
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}


</style>
