<template>
  <div id="app">
    <Slider />
    <Body />
  </div>
</template>

<script>
import Slider from './components/Slider.vue'
import Body from './components/Body.vue'


export default {
  name: 'app',
  components: {
    Slider,
    Body
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
}

body{
  margin:0px;
}
</style>
