<script setup>

const props = defineprops({
    programa: Object
});

</script>


<template>
    <h1>programas</h1>
    <Card style="width: 25rem; overflow: hidden">
        <template #header>
            <img alt="user header" src="images/Captura.PNG" />
        </template>
        <template #title>PROGRAMA{{ arregloDeProgramas.nombre }}</template>
        <template #subtitle>Card subtitle</template>
        <template #content>
            <p class="m-0">
               <p v-for="semillero in arregloDeProgramas.semilleros">
                <p>semillero {{semillero.semilleros}}</p>
                <p>cantidad de integrantes{{ semillero.CantIntegrantes }}</p>
               </p>
            </p>
            <Divider />
        </template>
        <template #footer>
            
        </template>
    </Card>
</template>

<script setup>
</script>






</template>