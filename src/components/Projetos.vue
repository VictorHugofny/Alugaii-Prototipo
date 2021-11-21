<template>
<div class="projeto">
  <h1> Nossos projetos recentes</h1>
  <p> Aqui estão nossos projetos com programação que trabalhamos recentemente.</p>
</div>
     
</template>

<script>
export default {
}
</script>

<style>
.projeto h1{
    font-size: 74px;
    color: rgba(8, 222, 255, 0.63) ;
    font-weight: bolder;
    text-align: center;
}
.projeto p{
    font-size: 26px;
    color: rgb(112, 236, 255) ;
    text-align: center;
}

.projeto{
    padding-top: 300px;
    padding-bottom: 300px;
    background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.753), rgba(0, 0, 0, 0.767)), url('../assets/gifrapida.gif');
    background-repeat: no-repeat;
    background-size: cover;
}
</style>