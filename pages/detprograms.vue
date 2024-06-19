<script setup>
import semillerosJson from "../data/Semillero_LosNadie.json";
const programas = semillerosJson[0];
</script>
<template>	
    <div class="m-4">	    
    <h1>Detalles programas</h1>
<detprograms :programas="programa"/> 
</div>	
</template>	