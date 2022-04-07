<template>
  <section class="contenedor-crear" id="crea">
		<h2>Crea tu pastel</h2><br>
			<h3 style="text-align: center;">Elige un pastel</h3><br>
			<!-- Swiper -->
            <div class="aling-pas">
   				  <div class="cont-pas">
						  <input type="radio" id="azul" name="pastel" value="azul">
						  <label for="azul"><img src="../assets/img/pastel1.svg"></label>
					  </div>
   				  <div class="cont-pas">
						  <input type="radio" id="rosa" name="pastel" value="rosa">
						  <label for="rosa"><img src="../assets/img/pastel2.svg"></label>
				    </div>
            </div>
            <div class="aling-pas">
   				  <div class="cont-pas">
						  <input type="radio" id="amarillo" name="pastel" value="amarillo">
						  <label for="amarillo"><img src="../assets/img/pastel3.svg"></label>
					  </div>
   				  <div class="cont-pas">
						  <input type="radio" id="verde" name="pastel" value="verde">
						  <label for="verde"><img src="../assets/img/pastel4.svg"></label>
					  </div>
            </div>
   				  <br><br><br>
			<h3 style="text-align: center;">Elige un adorno</h3><br>
				 <!-- Swiper -->
            <div class="aling-pas">
   				  <div class="cont-pas">
						  <input type="radio" >
						  <label for="azul"><img src="../assets/img/adorno1.png"></label>
					  </div>
   				  <div class="cont-pas">
						  <input type="radio" >
						  <label for="rosa"><img src="../assets/img/adorno2.png"></label>
				    </div>
            </div>
            <div class="aling-pas">
   				  <div class="cont-pas">
						  <input type="radio" >
						  <label for="amarillo"><img src="../assets/img/adorno3.png"></label>
					  </div>
   				  <div class="cont-pas">
						  <input type="radio" >
						  <label for="verde"><img src="../assets/img/adorno4.png"></label>
					  </div>
            </div>
   				  <br><br><br>
	</section>
    
</template>

<script>
export default {
  name: 'Crear',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

.contenedor-crear{
    margin-top: 5vh;
}    
a {
  color: #42b983;
}
.aling-pas{
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 30px;
  }
  .cont-pas{
    margin: 10px;
  }
</style>
