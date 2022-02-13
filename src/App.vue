<template>
  <div id="app">
    <div id="nav">
      <div>
        <router-link to="/">Principal</router-link> 
        <router-link to="/projetos">Plataforma </router-link> 
        <router-link to="/about">APP ALugaii</router-link> 
        <router-link to="/pedido">Pedido</router-link>
      </div>
     
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
  background-color: rgb(0, 0, 0);
  position: -webkit-sticky; /* Necessário para funcionar no Safari */
  position: sticky;
  top: 0;
  padding-top: 5px;
  padding-bottom: 5px;
  width: 100%;
  text-align: center;
  color:rgb(202, 202, 202);
  z-index: 10;
  display: flex;
  justify-content: center;
  align-items: baseline;
}


#nav a {
  text-decoration: none;
  padding: 6px;
  font-weight: bold;
  font-size: 20px;
  color: #757575;
}

#nav a.router-link-exact-active {
  color: #ff5353;
}

@media(max-width: 800px){
#nav a {
  font-size: 14px;
}

}


</style>
