<template>
  <div id="app">
    <Header></Header>
    <StockList></StockList>
    <ShoppingCart></ShoppingCart>
    <Payment></Payment>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import StockList from './components/StockList.vue'
import ShoppingCart from './components/ShoppingCart.vue'
import Payment from './components/Payment.vue'

export default {
  name: 'App',
  components: {
    Header,
    StockList,
    ShoppingCart,
    Payment
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
