<template>
  <div id="app">
    <Header class="header" msg="vicNYC"/>
    <Container/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Container from './components/Container.vue'

export default {
  name: 'app',
  components: {
    Header,
    Container,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: rgb(44, 168, 141);
  display: inline-block;
}

.header {
  border-bottom: solid 2px lavender;
}
</style>
