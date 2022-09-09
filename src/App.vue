<template>

  <h1>RIP BOZO</h1>
  <p>Rest in peace you'll not be missed</p>
  <!-- usando componente criado -->
  <!-- ao criar um componente -->
  <!-- o vue cria um tag própria para o componente -->
  <PrimeiroComponente/>
  <LifeCycle/>
  <CMPpessoa/>

</template>

<script>

import PrimeiroComponente from './components/PrimeiroComponente.vue';
import LifeCycle from './components/LifeCycle.vue';
import CMPpessoa from './components/CMPpessoa.vue';

export default {
  name: 'App',
  components:{
    PrimeiroComponente,
    LifeCycle,
    CMPpessoa
  }
}

</script>

<style>
 *{
  background-color: #42b983;
 }

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
