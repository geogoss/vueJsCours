<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <contenu-1></contenu-1>
</template>

<script>

import Contenu from './components/Contenu/Contenu-1.vue'


export default {
  name: 'App',
  components: {
    'contenu-1': Contenu,
  }
}
</script>

<style>
#app {
  /* on dégage ceci car ce n'est pas scoped et ça s'applique à tout */
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
