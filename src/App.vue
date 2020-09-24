<template>
  <div id="app">
    <Header />
    <Quiz />
    <LinkHolder />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Quiz from './components/Quiz.vue'
import LinkHolder from "./components/LinkHolder.vue";


export default {
  name: 'App',
  components: {
    Header,
    Quiz,
    LinkHolder
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
