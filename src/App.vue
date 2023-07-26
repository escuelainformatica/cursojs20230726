<script setup>
import Componente1 from './Componente1.vue';
import Tabla from './Tabla.vue';
import DatoEmpleado from './DatoEmpleado.vue';
import Boton from './Boton.vue';
</script>
<template>
  <Componente1/>
  <Tabla/>  
  <br>
  <hr>
  <DatoEmpleado/>
  <br>
  <hr>
  <Boton/>

</template>
<style>
  .etiqueta {
    width:200px;
    display: inline-block;
  }
  .contenido {
    font-weight: bold;
  }
</style>