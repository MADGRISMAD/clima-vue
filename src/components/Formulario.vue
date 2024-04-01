<script setup>
const paises = [
    { codigo: 'US', nombre: 'Estados Unidos' },
    { codigo: 'MX', nombre: 'México' },
    { codigo: 'AR', nombre: 'Argentina' },
    { codigo: 'CO', nombre: 'Colombia' },
    { codigo: 'CR', nombre: 'Costa Rica' },
    { codigo: 'ES', nombre: 'España' },
    { codigo: 'PE', nombre: 'Perú' }
]

</script>
<template>
    <form class="formulario
    ">
    <div class="campo">
        <label for="ciudad">ciudad</label>
        <input 
        type="text" 
        id="ciudad" 
        v-model="ciudad" 
        required>

    </div>
    <div class="pais">
        <label for="pais">País</label>
        <select value="">--seleccione un pais--</select>

    </div>
    
    </form>
</template>

