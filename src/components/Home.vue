<template>
<div class="topo">
    <div>
        <img class="foto" src="../assets/ABC.png" width="430" alt="" srcset="">
    </div>
    
    <div>
        <h1>Considerado o <br> melhor aplicativo. <br> para alugar produtos</h1>
    </div>
    
</div>
     
</template>

<style>
.topo{
    display: flex;
}
.topo h1{
    font-size: 52px;
    color: rgb(255, 255, 255) ;
    font-weight: bolder;
    text-align: center;
}
.topo p{
    margin-top: 10px;
    font-size: 24px;
    color: rgba(8, 222, 255, 0.63) ;
    font-weight: bolder;
    text-align: center;
}

.topo{
    background-image: linear-gradient(0deg, rgb(97, 2, 2) 0%, rgba(0, 2, 7, 0.822) 20%, rgb(0, 0, 0) 110%), url("../assets/fundo.jpg");;
    display: flex;
    padding-bottom: 50px;
    align-items: center;
    flex-direction: row-reverse;
    flex-wrap: wrap;
    justify-content: center;
}
.topo > div {
  padding-left: 10px;
  text-align: center;
}



@media(max-width: 800px){
.topo{
    background-repeat: no-repeat;
    background-size: cover;
}

}
</style>