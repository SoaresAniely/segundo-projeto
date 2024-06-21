<template>
  <img alt="Vue logo" src="./assets/Aniely Soares - Modelos de logo pr escolha (2).jpg">
  <HelloWorld msg=" "/>
  <ParteCimaVue msg=" "/>
  <ParteVideoVue msg=" "/>
  <ConteudoBrowVue msg=" "/>
  <parte-baixo msg=" "/>
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ParteVideoVue from './components/ParteVideo.vue'
import ParteBaixo from './components/ParteBaixo.vue'
import ParteCimaVue from './components/ParteCima.vue'
import ConteudoBrowVue from './components/ConteudoBrow.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    ParteVideoVue,
    ParteCimaVue,
    ParteBaixo, 
    ConteudoBrowVue
  }
}
</script>

<style>
#app {
  background-color: #dad1c5;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2f2f30;
  margin-top: none;
  width: 1300px;
  padding: 30px;
}
img {
   width: 300px;
   padding: 10px;
   position: relative;
}

</style>
