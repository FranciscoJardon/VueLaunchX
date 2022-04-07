<template>
  <section><br><br>
			<h2 id="pedidos">Pedidos</h2> 
				<div id="pedido1"> 
					<h3>Roberto Martinez</h3>
					<p>
						roberto_martinez@gmail.com 
						<br><br>
						55 32455689
					</p>	
					<p>Descripción: Lorem ipsum dolor sit amet, consectetur adipiscing elit ut aliquam</p>
					<div class="aling-img"><img src="../assets/img/pastel4.svg">	
					<img src="../assets/img/adorno3.png"></div>
				</div>
				<div id="pedido2">
					<h3>Diego Ruzarin</h3>
					<p>
						diego-ruz@gmail.com 
						<br><br>
						55 324536589
					</p>	
					<p>Descripción: Lorem ipsum dolor sit amet, consectetur adipiscing elit ut aliquam</p>
					<div class="aling-img"><img src="../assets/img/pastel2.svg">	
						<img src="../assets/img/adorno1.png"></div>
				</div><br><br>
		</section>
</template>

<script>
export default {
  name: 'Pedidos',
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
