<template>
  <div id="app">
    <Header @ricerca="ricercafilm" />
    <Main />
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'
// import axios from "axios"

export default {
  name: 'App',
  components: {
    Main,
    Header
  },
  methods: {
    ricercafilm (text) {
      console.log(text)
    }
  },
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
