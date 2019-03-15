<template>
  <div id="app">
    <vue-header></vue-header>
   <vue-table></vue-table>
    <router-view/>
  </div>
</template>

<script>
import header from './components/common/Header'
import table from './components/common/Tabbar'
export default {
  name: 'App',
  components:{
    vueTable:table,
    vueHeader:header
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
