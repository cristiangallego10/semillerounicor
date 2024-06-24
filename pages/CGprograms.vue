<script setup>
const arregloDeProgramas = [
    {
        nombre:"Licenciatura en Informatica",
        semilleros:[
            "AVI",
            "Bimadimo",
            "Lab de IA",

        ],
       
    },
    {
        nombre:"Licenciatura en ciencias sociales",
        semilleros:[
            "socialboys",
        ]
    }
]
</script>
<template>
    <CGcomprograms v-for="programaActual in arregloDeProgramas" :programa="programaActual" /> 
</template>	