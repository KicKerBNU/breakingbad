<template>
  <div id="app">
    <HelloWorld></HelloWorld>
  </div>
</template>

<script>
import "beercss";
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
body {
 background-image: url("./assets/money.jpg");
 background-attachment: fixed;
 background-position: 50% 25%;
 
}
</style>
