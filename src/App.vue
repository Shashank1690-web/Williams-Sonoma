<template>
  <Header />
  <Products />
</template>

<script>
import Products from './components/Products.vue'
import Header from './components/Header.vue'
export default {
  name: 'App',
  components: {
    Header,
    Products
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
}
</style>
