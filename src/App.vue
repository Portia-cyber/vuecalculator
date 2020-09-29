<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" class="logo">
  <calculator></calculator>
  </div>
</template>

<script>
import Calculator from './components/Caculator.vue'

export default {
  name: 'App',
  components: {
    Calculator
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.logo{
  margin: 0 auto;
  height: 30px;
  display: block;
  padding-bottom: 40px;
}
</style>
