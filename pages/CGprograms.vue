<script setup>

const arregloDeProgramas = [
    {
        nombre: "Licenciatura en Informatica",
        semilleros: [
            "AVI",
            "Bimadimo",
            "Lab de IA",

        ],
       CantIntegrantes: "90"
    },
    {
        nombre:"Licenciatura en Educación Artistica",
        semilleros:[
            "EXPRESARTE",
            "Músicas tradicionales y cultura popular",

        ],
        CantIntegrantes: "65"
    },
    {
        nombre: "DEPARTAMENTO DE CIENCIAS NATURALES Y EDUCACIÓN AMBIENTAL",
        semilleros:[
            "DIDACIEN",
            "EdAmSis",
            "GIAM-UNICOR",
        ],
        CantIntegrantes: "120"
    }
    
]
</script>
<template>
    <h1>PROGRAMAS</h1>
    <CGcomprogramas :arregloDeProgramas="programa"/>
 </template>	