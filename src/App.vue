<template>
  <div id="app">
    <example-component></example-component>
  </div>
</template>

<script>
import ExampleComponent from './components/example-component.vue'

export default {
  name: 'app',
  components: {
    ExampleComponent
  }
}
</script>

<style>
  body, html {
    margin: 0;
    padding: 0;
    height: 100%;
  }

  body {
    color: #2c3e50;
  }

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    display: flex;
    height: 100%;
  }
</style>
