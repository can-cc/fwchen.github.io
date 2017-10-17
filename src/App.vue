<template>
  <div id="app">
    <ChenPage />
  </div>
</template>

<script>
import ChenPage from './components/ChenPage'

export default {
  name: 'app',
  components: {
    ChenPage
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
