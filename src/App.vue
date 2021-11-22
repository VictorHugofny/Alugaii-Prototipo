<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/projetos">Projetos</router-link> |
      <router-link to="/about">Responsaveis</router-link> |
      <router-link to="/pedido">Pedido</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
*{
  margin:0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  background-color: black;
  padding: 10px;
}

#nav a {
  font-weight: bold;
  font-size: 18px;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #4283b9;
}

@media(max-width: 800px){
#nav a {
  font-size: 14px;
}

}


</style>
