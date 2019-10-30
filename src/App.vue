<template>
  <div id="app">

    <HelloWorld/>
    <k/>
    <shui/>
    <list/>
    <cart/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import k from './components/k'
import shui from './components/shui'
import list from "./components/list.vue"
import cart from "./components/cart.vue"
export default {
  name: 'App',
  components: {
    HelloWorld,
    k,
    shui,
    list,
    cart
  }
}



</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
