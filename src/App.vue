<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld 
  msg="Howdy!"
  bodyText=" Esto es un mensaje de prueba"
  />
  <FooterComponent message="Hola Ctmmm"></FooterComponent>
</template>


<script>
import HelloWorld from './components/HelloWorld.vue'
import FooterComponent from './components/FooterComponent.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    FooterComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
