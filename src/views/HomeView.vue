<template>
  <div class="home">
    <Descripcion/>
    <Crear/>
    <Formulario/>
    <Contacto/>
  </div>
</template>

<script>
// @ is an alias to /src

import Descripcion from '@/components/Descripcion.vue'
import Crear from '@/components/Crear.vue'
import Formulario from '@/components/Formulario.vue'
import Contacto from '@/components/Contacto.vue'

export default {
  name: ' Descripcion Crear Formulario Contacto', 
  components: {
    Descripcion, 
    Crear,
    Formulario,
    Contacto
  }
}
</script>
