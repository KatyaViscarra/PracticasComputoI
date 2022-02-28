<template>
  <div id="app">
      <!--list-products title="List Products"/>
      <cart-items :cartItems="cartItems" :itemCount="itemCount"-->
        
      <life-cycle/>
  </div>
</template>

<script>
//import CartItems from './components/CartItems.vue'
//import ListProducts from './components/ListProducts.vue'
import LifeCycle from './components/LifeCycle.vue'

export default {
  name: 'App',
  components: {
    //ListProducts,
    //CartItems
    LifeCycle
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