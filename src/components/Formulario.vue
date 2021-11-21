<template>
<div class ='formulario'>
  <h1>Faça seu pedido abaixo, logo apos iremos retornar uma resposta por email</h1>
    <form>   
    <h2>Nome completo</h2>
    <input type="text" id="lname" name="lname" >
    <h2>Email</h2>
    <input type="email" name="" id="">
    <h2>Pedido</h2>
    <div class = 'pedido'>
    <input type="text" id="pedido" name="pedido"><br><br>
    </div>
    <button> Enviar </button>
    </form>
</div>
</template>

<script>
export default {

}
</script>

<style>
.formulario{
    padding-top: 100px;
    padding-bottom: 150px;
    background-color: rgb(0, 171, 194);
}
.formulario h1{
    color: white;
    padding-bottom: 50px;
}
.formulario h2{
    color: white;
    padding-bottom: 20px;
}
.formulario input{
    width: 240px;
    height: 30px;
}
.pedido input{
    width: 240px;
    height: 130px;
}
.formulario button{
    background-color: rgb(0, 0, 0);
    color: rgb(0, 209, 246);
    font-weight: bolder;
    font-size: 18px;
    padding: 16px;
    padding-left:80px;
    padding-right: 80px;
    border: rgba(0, 0, 0, 0.349) solid 1px;
    border-radius: 10px;
    
}

</style>