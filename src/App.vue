<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Rony in Vue Js "/>
  <!-- <HomeComponent/> -->
  <InterpolationAndData/>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// import HomeComponent from './components/Home.vue'
import InterpolationAndData from './components/Interpolation.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    // HomeComponent,
    InterpolationAndData
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
