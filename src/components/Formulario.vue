<template>
  <section class="aling-center">
		<div class="contenedor-form">
					<form action="" method="post" class="form">
					<input class="input"  type="text" name="name" id="name" placeholder="Nombre" required="">
					<input class="input"  type="email" name="email" id="mail" placeholder="Correo" required="">
					<input class="input"  type="number" name="tel" id="tel" placeholder="Teléfono" required="">
					<textarea  class="input" name="mensaje" id="message" cols="30" rows="10" 	placeholder="Descripción del Pastel" required=""></textarea>
					<input class="input"  type="submit" value="Realizar Pedido">
					</form>
		</div>
  </section>
</template>

<script>
export default {
  name: 'Formulario',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.aling-center{
    display: flex;
    justify-content: center;
}
.contenedor-form{
    width: 100vw;
    max-width: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.form{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.input{
    background: #95DCFF;
    border-radius: 5px;
    color: #fff;
    outline: none;
    border: none;
    padding: 15px 10px;
}

.input::placeholder{
    color: #fff;
    
    font-size: small;
}

input[type="text"], 
input[type="email"],
input[type="number"]{
    display: inline-block;
    width: 80%;
    margin-bottom: 15px;
}

.form textarea{
   width: 80%;
    margin-bottom: 15px;
}

input[type="submit"]{
    width: 120px;
    text-align: center;
    padding: 14px 0;
}

input[type="submit"]:hover{
    cursor: pointer;
    color: tomato;
    background: #fff;
    color: #667a62;
}
a {
  color: #42b983;
}
</style>
