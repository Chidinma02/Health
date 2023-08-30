<template>
  <div id="app">
   <HelloWorld></HelloWorld>
    <router-view/>
    <HomeFooter></HomeFooter>
  </div>
</template>
<script>
import HelloWorld from './components/HelloWorld.vue';
import HomeFooter from './components/HomeFooter.vue';
export default {
  
   components: {
   HelloWorld, HomeFooter
  }
}
</script>
<style>
@font-face {
  font-family: 'CustomFont'; /* Provide a name for your font */
  src: url('./assets/font/Inter-VariableFont_slnt\,wght.ttf') format('ttf');
     
  font-weight: normal;
  font-style: normal;
}
 *{
	font-family:'CustomFont';
  /* color:#258576; */
 }
*{
  padding: 0px ;
  MARGIN:0px ;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  
}



</style>
