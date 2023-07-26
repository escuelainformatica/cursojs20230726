<script setup>
import { ref} from 'vue';
let contador=ref(0); // contador que el valor se guarda en un campo value

function clickboton() {
    contador.value=contador.value+1;
}

</script>
<template>
    contador:{{ contador }}<br>
    <button @click="clickboton">incrementar</button>
</template>
<style>
</style>