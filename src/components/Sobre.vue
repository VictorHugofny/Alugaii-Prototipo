<template>
  <div class='sobre'>
      <div>      
          <img class = "img" src="../assets/banner.png" alt="" width="410" srcset="">
    </div>

      <div class = "app"><h2>Baixe o APP agora !!!</h2>
        <p>Não fique de fora, venha conferir os produtos que você pode locar !!!</p>
        <img src="../assets/playstore.png" width="200" alt="">
      </div>
      
  </div>
</template>

<style>
.sobre h2{
    color: aliceblue;
}
.sobre h1{
    color: rgb(255, 255, 255);
    padding-bottom: 30px;
    text-align: center;
    font-size: 46px;
    padding-left: 20px;
    padding-right: 20px;
}
.sobre strong{
    color: rgb(0, 225, 255);
}
.sobre {
    background: rgb(0, 0, 0);
    margin-top: 100px;
    margin-bottom: 100px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    border: 3px solid rgb(36, 36, 36);
    margin-bottom: 30px;
    align-items: center;
}
.sobre p{
    color: rgb(255, 255, 255);
    text-align: center;
    font-size: 26px;
    padding-left: 20px;
    padding-right: 20px;  
}
body{
    background-color: rgb(0, 0, 0);
}


.sobre div{
    margin-bottom: 0px;
}
.sobre .app{
    background: black;
}

</style>