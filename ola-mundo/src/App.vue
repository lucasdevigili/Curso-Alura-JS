<template>
   <main class="columns is-gaplass is-multiline">
     <div class="column is-one-quarter">
       <barra-lateral />
     </div>
     <div class="column is-three-quarter">
       <formulario />
       <formulario />
       <formulario />
     </div>
   </main>
</template>

<script lang='ts'>
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue';
import Formulario from './components/Formulario.vue'



export default  defineComponent({
  name: 'App',
  components: {
    BarraLateral,
    Formulario
  }

})
</script>
