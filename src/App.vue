<template>
  <div id="app">
   <ye/>
   <father></father>
    <router-view/>
  </div>
</template>

<script>
import ye from '@/yeye'
import father from '@/father'
export default {
  name: 'App',
  components:{
    ye,
    father
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
