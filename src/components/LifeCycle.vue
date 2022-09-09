<template>
    <h1>meu nome é: {{nome}} </h1>
</template>

<script> 
    export default{
    name: 'LifeCycle',
    data(){
        return{
            nome: 'SIUUUUUUUU'
        }
    },
    created() {
        this.nome = 'Matheus'
    }
}
</script>