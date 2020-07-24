<template>
  <div id="app">
    <DataPage />
  </div>
</template>

<script>
import DataPage from './view/DataPage.vue'

export default {
  name: 'App',
  components: {
    DataPage
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
