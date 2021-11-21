<template>
  <div id="app">
    <Home/>
    <Sobre/>
    <Projetos/>
    <ListaProjetos/>
    <Formulario/>
    <Contatos/>

  </div>
</template>

<script>
import Home from './components/Home.vue'
import Projetos from './components/Projetos.vue'
import Sobre from './components/Sobre.vue'
import ListaProjetos from './components/ListaProjetos.vue'
import Formulario from './components/Formulario.vue'
import Contatos from './components/Contatos.vue'




export default {
  name: 'App',
  components: {
    Home,
    Projetos,
    Sobre,
    ListaProjetos,
    Contatos,
    Formulario
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(8, 222, 255);
}
*{
  margin:0;
}
</style>
