<template>
  <div id="app">

    <Plan msg="Mensa-FOOOD"/>
  </div>
</template>

<script>
import Plan from './views/Plan.vue'

export default {
  name: 'App',
  components: {
  // eslint-disable-next-line vue/no-unused-components
  Plan
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
