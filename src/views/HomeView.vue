<template>
  <div class="home">
    <img class="logos" alt="Logo del IMSS" src="../assets/imsslogo.png">
    <img class="logos" alt="Logo del Conalep" src="../assets/logoconalep.png">
    <HelloWorld msg="Inventario de Enfermeria UMF No.17"/>
  </div>
</template>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
  },
};
</script>
<style>
  .logos {
    width: 180px;
    height: 200px;
    margin: 1em;
  }
</style>
