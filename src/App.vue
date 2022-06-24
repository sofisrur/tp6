<template>
  <div id="app">
    <Header/>
 <!--    <Navigator/>
    <Container/> -->
  </div>
</template>

<script>
import "bootstrap"
import "jquery"
import "popper.js"
import "bootstrap/dist/css/bootstrap.min.css"

import Header from '../src/componentes/Header.vue'
/* import Navigator from '../src/componentes/Navigator.vue'
import Container from '../src/componentes/Container.vue' */

export default {
  name: 'App',
  components: {
    Header,
  /*   Navigator,
    Container */
  },
  data(){
    return{
    }
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
  body {
	background: #232323;
	margin: 0;
	font-family: "Montserrat", "Avenir";
}
</style>
