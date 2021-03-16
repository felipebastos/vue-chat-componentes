<template>
    <div class="exemplo">
        <h1 @click="clique()">Olá, {{nome}}!</h1>
    </div>
</template>

<script>
export default {
    name: 'Nosso',
    data: function(){
        return {
            nome: 'turma'
        }
    },
    methods:{
        clique: function(){
            alert('Clicou!')
        }
    }
}
</script>

<style scoped lang="sass" src="../sass/estilo.sass"></style>