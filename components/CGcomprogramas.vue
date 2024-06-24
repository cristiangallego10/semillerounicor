<script setup>

const props = definirprops({
    programa: Object
});

</script>

<template>
    <Card>
    <template #title>{{ programa.nombre }}</template>
    <template #content>
        <h1>semilleros</h1>
        <p class="m-0">
         {{ programa.semilleros }}
        </p>    
    </template>
</Card>





</template>