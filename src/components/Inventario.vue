<template>
  <section>
			<h2>Inventario</h2>
				<h3>Pasteles</h3>
				<div class="aling-pas">
   				  <div class="cont-pas">
						  <img src="../assets/img/pastel1.svg">12
					  </div>
   				  <div class="cont-pas">
						 <img src="../assets/img/pastel2.svg">15
					  </div>
            	</div>
				<div class="aling-pas">
   				  <div class="cont-pas">
						  <img src="../assets/img/pastel3.svg">16
					  </div>
   				  <div class="cont-pas">
						 <img src="../assets/img/pastel4.svg">09
					  </div>
            	</div>
			
				<h3>Adornos</h3>
					<div class="aling-pas">
   				  <div class="cont-pas">
						  <img src="../assets/img/adorno1.png">112
					  </div>
   				  <div class="cont-pas">
						 <img src="../assets/img/adorno2.png">315
					  </div>
            	</div>
				<div class="aling-pas">
   				  <div class="cont-pas">
						  <img src="../assets/img/adorno3.png">216
					  </div>
   				  <div class="cont-pas">
						 <img src="../assets/img/adorno4.png">109
					  </div>
            	</div>
	</section>
</template>

<script>
export default {
  name: 'Inventario',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>


.aling-pas{
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 30px;
  }
  .cont-pas{
    margin: 15px;
  }

a {
  color: #42b983;
}
</style>
