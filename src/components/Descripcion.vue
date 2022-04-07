<template>
  <section class="contenedor-home" @id="inicio">
		<div class="contenedor-logo">
			<h1>JrCake</h1>
			<p>Fresco y delicioso porque te mereces lo mejor, haz tu día más feliz.</p>
		</div >
    <img class="img-inicio"  src="../assets/img/persona.svg">
	</section>
</template>

<script>
export default {
  name: 'Descripcion',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1 {
  margin: 40px 0 0;
}

.contenedor-home{
    display: flex;
    align-items: center;
    justify-content: center;
} 
.contenedor-logo{
    position: relative;
    display: inline-block;
    width: 40vw;
    max-width: 250px;
}
.img-inicio{
 margin-left: 20px; 
 width: 240px;
}

a {
  color: #42b983;
}
</style>
