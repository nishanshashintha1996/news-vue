<template>
  <div id="app">
    <nav-bar></nav-bar>
    <news-grid></news-grid>
    <news-grid></news-grid>
    <news-grid></news-grid>
  </div>
</template>

<script>
  import Navbar from './components/Nav.vue'
  import NewsGrid from './components/NewsGrid.vue'
  export default {
    name: 'app',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App',
        color: 'red'
      }
    },
    components: {
      'nav-bar' : Navbar,
      'news-grid' : NewsGrid
    }
  }
</script>

<style>

</style>
