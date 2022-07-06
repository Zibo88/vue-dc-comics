<template>
  <div id="app">
    <MyHeader/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
 import MyHeader from './components/MyHeader.vue'

export default {
  name: 'App',
  components: {
    MyHeader
  }
}
</script>

<style lang="scss">
// importo gli stili da common
@import './style/common'
</style>
