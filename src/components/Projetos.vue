<template>
<div class="projeto">
  <h1>Já disponível na Playstore</h1>
  <p> Baixe o App e tenha em suas mãos a possibilidade de locar objetos em poucos minutos, assim você pode aproveitar ao máximo seu item</p>
  <br>
  <p> pagando pouco e sem a necessidade de comprar e depois deixar ele parado em sua casa. </p>
</div>
     
</template>

<script>
export default {
}
</script>

<style>
.projeto h1{
    font-size: 54px;
    color: rgb(255, 0, 0) ;
    font-weight: bolder;
    text-align: center;
}
.projeto p{
    font-size: 24px;
    color: rgb(255, 255, 255) ;
    text-align: center;
}

.projeto{
    padding-top: 100px;
    padding-bottom: 100px;
    background-image: linear-gradient(0deg, rgb(0, 0, 0) 0%, rgba(0, 8, 26, 0.739) 60%, rgb(0, 0, 0) 100%), url('../assets/frente.jpg');
    background-repeat: no-repeat;
    background-size: cover;
   
}

@media(max-width: 800px){


}
</style>