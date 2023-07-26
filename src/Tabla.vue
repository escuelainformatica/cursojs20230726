<script setup>
let empleados = [
    { nombre: "Emily Davis", titulo: "Sr.Manger", UnidadNegocio: "Research&development" },
    { nombre: "Theodore ", titulo: "Technical Architectr", UnidadNegocio: "Manufacturing" },
    { nombre: "Luna Sanders", titulo: "Director", UnidadNegocio: "Speciality Products" },
    { nombre: "Penelope Jordan", titulo: "Computer Systems Manager", UnidadNegocio: "Manufacturing" },
];
</script>
<template>
    <table border="1">
        <thead>
            <tr>
                <th>nombre</th>
                <th>titulo</th>
                <th>Unidad Negocio</th>
            </tr>
        </thead>
        <tbody>
            <tr v-for="fila in empleados">
                <td>{{ fila.nombre }}</td>
                <td>{{ fila.titulo }}</td>
                <td>{{ fila.UnidadNegocio }}</td>
            </tr>
        </tbody>
    </table>
</template>
<style></style>