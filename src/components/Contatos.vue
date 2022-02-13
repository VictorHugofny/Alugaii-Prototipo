<template>
<div class = 'contatos'>
  <h1>A Plataforma</h1>
  <p>Esse é a plataforma que faltava para você conseguir os objetos de maneira fácil e assim</p>
  <br> <br>
<div class = 'container1'>

  <div class="card1">
    <img src="../assets/telefone.gif" alt="John" style="width:100%">
    <h2>Alugaii</h2>
    <p class="title">Você pode alugar brinquedos, carros, roupas e etc.. </p>
    <p><button>FALE COM A GENTE</button></p> 
  </div>


</div>
</div>
</template>


<style>
.contatos h1{
    font-size: 54px;
    color: rgba(255, 78, 78, 0.986) ;
    font-weight: bolder;
    text-align: center;
}
.contatos p{
    margin-top: 20px;
    font-size: 24px;
    color: rgb(255, 255, 255) ;
    font-weight: bolder;
    text-align: center;
}
.container1{
    display: flex;
    margin-bottom: 0px;
    justify-content: space-evenly;
}

.container1 > div {
  margin-left: 5px;
  margin-right: 5px;
  margin-bottom: 10px;
  flex: 10 10 50%;
  text-align: center;
  border: rgb(163, 1, 1) 3px solid;
  border-radius: 10px;
}

.container1{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    margin-left: 15px;
    margin-right: 15px;
}


.contatos{
  padding-top: 20px;
  padding-bottom: 20px;
  background-image: linear-gradient(0deg, rgba(245, 24, 24, 0.39) 10%, rgb(0, 0, 0) 50%, rgba(0, 0, 0, 0.39) 100%)


}
.card1 {
  box-shadow: 0 4px 8px 0 rgba(255, 0, 0, 0.2);
  background-color: rgb(255, 255, 255);
  max-width: 360px;
  margin: auto;
  text-align: center;
  font-family: arial;
}

.card1 .title {
  color: grey;
  font-size: 18px;
}

.card1 button {
  outline: 0;
  display: inline-block;
  padding: 10px;
  width: 100%;
  margin-left:0px;
  color: white;
  background-color: rgb(109, 0, 0);
  text-align: center;
  cursor: pointer;
  font-size: 18px;
  border-radius: 0;
  border: 0;
}

.card1 a {
  text-decoration: none;
  margin: 4px;
  padding-left:14px;
  font-size: 22px;
  color: rgb(122, 0, 0);
}

.card1 button:hover, a:hover {
  opacity: 0.7;
}

</style>