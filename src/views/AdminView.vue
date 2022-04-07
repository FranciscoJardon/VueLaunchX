<template>
  <div class="admin">
    <Inventario/>
    <Pedidos/>
    
  </div>
</template>

<script>
// @ is an alias to /src

import Inventario from '@/components/Inventario.vue'
import Pedidos from '@/components/Pedidos.vue'

export default {
  name: 'Inventario Pedidos', 
  components: {
   Inventario,
   Pedidos,

  }
}
</script>