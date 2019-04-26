<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <BPI></BPI>
  </div>
</template>

<script>
import BPI from './components/BPI.vue'

export default {
  name: 'app',
  components: {
    BPI
  }
}
</script>

<style lang="scss">
#app {
  font-family: $font-stack;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $primary-dark;
  margin-top: 60px;
}
</style>
