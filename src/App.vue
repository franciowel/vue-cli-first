<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <myMessage msg="La mia prima app con Vue CLI, modifica h1"/>
  </div>
</template>

<script>
import myMessage from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    myMessage
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
</style>
