<template>
  <div id="app">
    <Agenda />
  </div>
</template>

<script>
import Agenda from '../src/components/Agenda.vue'

export default {
  name: 'App',
  components: {
    Agenda
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
