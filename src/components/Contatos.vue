<template>
<div class = 'contatos'>
  <h1>Equipe - OraiteDev</h1>
  <p> Abaixo o perfil dos donos/desenvolvedores</p>
  <br> <br>
<div class = 'container1'>

  <div class="card1">
    <img src="../assets/hugo.jpeg" alt="John" style="width:100%">
    <h2>Victor Hugo</h2>
    <p class="title">Desenvolvedor Web & Editor AudioVisual</p>
    <a href="#"><i class="fa fa-github"></i></a>
    <a href="#"><i class="fa fa-linkedin"></i></a>
    <a href="#"><i class="fa fa-instagram"></i></a>
    <a href="#"><i class="fa fa-envelope"></i></a>
    <p><button>Contact</button></p>
  </div>

  <div class="card1">
    <img src="../assets/Luis.jpeg" alt="John" style="width:100%">
    <h2>Luis Henrique</h2>
    <p class="title">Desenvolvedor Web & Designer Grafico</p>
    <a href="#"><i class="fa fa-github"></i></a>
    <a href="#"><i class="fa fa-linkedin"></i></a>
    <a href="#"><i class="fa fa-instagram"></i></a>
    <a href="#"><i class="fa fa-envelope"></i></a>
    <p><button>Contact</button></p>
  </div>

  <div class="card1">
    <img src="../assets/marcos.png" alt="John" style="width:100%">
    <h2>Marcos Santos</h2>
    <p class="title">Desenvolvedor Web & Designer Grafico</p>  <a href="#"><i class="fa fa-github"></i></a>
    <a href="#"><i class="fa fa-linkedin"></i></a>
    <a href="#"><i class="fa fa-instagram"></i></a>
    <a href="#"><i class="fa fa-envelope"></i></a>
    <p><button>Contact</button></p>
  </div>

</div>
</div>
</template>


<style>
.contatos h1{
    font-size: 54px;
    color: rgba(8, 222, 255, 0.63) ;
    font-weight: bolder;
    text-align: center;
}
.contatos p{
    margin-top: 20px;
    font-size: 24px;
    color: rgba(8, 222, 255, 0.63) ;
    font-weight: bolder;
    text-align: center;
}
.container1{
    display: flex;
    margin-bottom: 100px;
    justify-content: space-evenly;
}

.container1 > div {
  margin-left: 5px;
  margin-right: 5px;
  margin-bottom: 10px;
  flex: 10 10 50%;
  text-align: center;
  border: rgb(1, 139, 163) 3px solid;
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

}
.card1 {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  background-color: rgb(255, 255, 255);
  max-width: 260px;
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
  background-color: rgb(0, 69, 109);
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
  color: rgb(0, 88, 122);
}

.card1 button:hover, a:hover {
  opacity: 0.7;
}

</style>