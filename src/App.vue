<template>
  <div id="app">
    <One></One>
    <Two></Two>
    <Three></Three>
    <Four></Four>
    <Five></Five>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import One from './components/One.vue'
import Two from './components/Two.vue'
import Three from './components/Three'
import Four from './components/Four.vue'
import Five from './components/Five'
export default {
  name: 'app',
  components: {
    // HelloWorld,
    One,
    Two,
    Three,
    Four,
    Five
  }
}
</script>

<style>
#app {
  
}
</style>
