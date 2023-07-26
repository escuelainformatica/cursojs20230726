<script setup>

let empleado = {
    nombre: "Emily Davis",
    trabajo: "Sr. Manger",
    Departamento: "IT",
    UnidadNegocio: "Research & Development",
    Raza: "Black",
    Edad: 55
}
</script>
<template>
    <span class="etiqueta">nombre:</span><span class="contenido">{{ empleado.nombre }}</span><br>
    <span class="etiqueta">trabajo:</span><span class="contenido">{{ empleado.trabajo }}</span><br>
    <span class="etiqueta">Departamento:</span><span class="contenido">{{ empleado.Departamento }}</span><br>
    <span class="etiqueta">Unidad de Negocio:</span><span class="contenido">{{ empleado.UnidadNegocio }}</span><br>
    <span class="etiqueta">Raza:</span><span class="contenido">{{ empleado.Raza }}</span><br>
    <span class="etiqueta">Edad:</span><span class="contenido">{{ empleado.Edad }}</span><br>
</template>
<script>
</script>