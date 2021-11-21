<template>
<div class = "container"> 
    <div class="card">
        <img src="../assets/gifhugo.gif" alt="Denim Jeans" width= "300px" height="220px">
        <h1>Portifolio - Victorhugofny</h1>
        <p>Portifolio Pessoal com meus estudos/projetos</p>
            <div class='button'>
                <button>SITE</button>
                <button>REPOSITORIO</button>
            </div>
    </div>

    <div class="card">
        <img src="../assets/luisgif.gif" alt="Denim Jeans" width= "300px" height="220px"> 
        <h1>Portifolio - Luis Henrique</h1>
        <p>Portifolio Pessoal com meus estudos/projetos</p>
            <div class='button'>
                <button>SITE</button>
                <button>REPOSITORIO</button>
            </div>
    </div>

    <div class="card">
        <img src="../assets/gifmarcos.gif" alt="Denim Jeans" width= "300px" height="220px"> 
        <h1>Portifolio - Marcos Santos</h1>
        <p>Portifolio Pessoal com meus estudos/projetos</p>
            <div class='button'>
                <button>SITE</button>
                <button>REPOSITORIO</button>
            </div>
    </div>

    
</div> 

</template>

<style>

.container{
    display: flex;
    margin-top: 150px;
    margin-bottom: 150px;
}
.container h1,p{
    color: black;
}
.card {
  border: rgb(0, 195, 255) 3px solid;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  width: 300px;
  margin: auto;
  text-align: center;
  font-family: arial;
  background-color: rgb(255, 255, 255);
}

.price {
  color: grey;
  font-size: 22px;
}

.card button {
  margin-top: 10px;
  border: none;
  outline: 0;
  padding: 12px;
  color: white;
  background-color: rgb(29, 29, 29);
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

.card button:hover {
  opacity: 0.7;
}

.button{
display: flex;
}
</style>