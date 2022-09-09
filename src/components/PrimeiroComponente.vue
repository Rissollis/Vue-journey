<!-- HTML GOES HERE,-->
<template>
    <h1>usando vue né</h1>
    <p>Meu nome é {{ nome }}</p>
</template>

<!-- JS GOES HERE -->
<script>
 export default{
    name: 'PrimeiroComponente',
    data() {
        return{
            nome: "Tchongos 1º"
        }
    }
 }
</script>

<!-- AND CSS GOES HERE!! -->
<style>
    h3 {
    margin: 40px 0 0;
    }

    ul {
    list-style-type: none;
    padding: 0;
    }

    li {
    display: inline-block;
    margin: 0 10px;
    }

    a {
    color: #42b983;
    }
</style>