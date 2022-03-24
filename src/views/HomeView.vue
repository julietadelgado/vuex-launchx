<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    
    <Contador/>
    <Exponente/>
    <Botones/>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Contador from '@/components/Contador.vue'
import Exponente from '@/components/Exponente.vue'
import Botones from '@/components/Botones.vue'

export default {
  name: 'HomeView',
  components: {
    Contador,
    Exponente,
    Botones
  }
  /*data(){
    return {
      contador: 0
    }
  },*/
  /*methods: {
    bajarContador(){
      this.contador--;
    },
    subirContador(){
      this.contador++;
    }
  }*/
}
</script>

<style>
  div { margin-bottom: 10px; } 
  .contador { font-size: 80px; }
  .botones button{ font-size: 40px; width: 100px; margin: 0 10px; }
  .exponencial { font-size: 25px; }
</style>