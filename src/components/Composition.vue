<script setup>
import { ref, onMounted, computed, reactive } from 'vue'

const name = ref('John')

const personagem = reactive({
    nome: 'Jason Duval',
    idade: 20,
    sexo: 'Masculino'
})

</script>

 
<template>
    <h1>Composition</h1>
    <h3>{{ personagem.nome }}</h3>
    <input type="text" v-model="personagem.nome">
    <input type="text" v-model="personagem.idade">
    <input type="text" v-model="personagem.sexo">
    <br>
    
</template>


<style scoped>

</style>