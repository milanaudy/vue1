<template>
  <!-- <img alt="Vue logo" src="./assets/1.jpg"> -->
  <HeaderComponents msg="vazne to funguje s componentami "/>


  
  <HelloWorld msg="vazne to funguje "/>

  <FooterComponent msg="vazne to funguje s componentami "/>
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HeaderComponents from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue';


export default {
  name: 'App',
  components: {
    HelloWorld,
    HeaderComponents,
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
