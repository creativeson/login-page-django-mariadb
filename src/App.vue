<template>
  <div id="app">
    <LoginPanel />
  </div>
</template>

<script>
import LoginPanel from './components/LoginPanel.vue'

export default {
  name: 'App',
  components: {
    LoginPanel
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
