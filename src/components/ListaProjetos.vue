<template>
<div class = "container"> 
    <div class="card">
        <img src="../assets/feramentas.jpg" alt="Denim Jeans" width= "300px" height="220px">
        <h1>Ferramentas</h1>
        <p>Aqui você encontra ferramentas para fazer aquele conserto rápido.</p>
    </div>

    <div class="card">
        <img src="../assets/treinos.jpg" alt="Denim Jeans" width= "250px" height="220px">
        <h1>Esportes</h1>
        <p>A Academia pode ir até você, confira os equipamentos e agende o seu.</p>
    </div>

    <div class="card">
        <img src="../assets/festas.jpeg" alt="Denim Jeans" width= "300px" height="220px">
        <h1>Festas</h1>
        <p>Encontre os materias perfeitos para casamento, aniversário e muito mais.</p>
    </div>

   
</div> 

</template>

<style>
.container{
    padding-top: 100px;
    padding-bottom: 100px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    background-image: linear-gradient(0deg, rgba(0, 0, 0, 0.39) 10%, rgba(255, 0, 0, 0.39) 50%, rgba(255, 0, 0, 0.39) 100%)
}
.container > div {
  margin-left: 30px;
  margin-right: 10px;
  margin-bottom: 30px;
  flex: 10 10 30%;
  text-align: center;
  border: rgb(255, 73, 73) 3px solid;
  border-radius: 10px;
}
.container h1,p{
    color: black;
}
.card {
  max-width: 300px;
  border: rgb(255, 0, 0) 3px solid;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  width: 300px;
  text-align: center;
  font-family: arial;
  background-color: rgb(2, 0, 0);
}
.card h1{
    color:white;
    margin-bottom: 20px;
}
.card p{
    color:white;
    margin-bottom: 20px;
}
.price {
  color: grey;
  font-size: 22px;
}


.card a{
    width: 100%;
}

.card button:hover {
  opacity: 0.7;
}

.button{
display: flex;
}
</style>