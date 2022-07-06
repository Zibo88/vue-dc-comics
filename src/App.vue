<template>
  <div id="app">
    <header>
      <MyHeader/>
    </header>

    <main>
      <MainCard/>
    </main>
    
  </div>
</template>

<script>

 import MyHeader from './components/MyHeader.vue'
import MainCard from './components/MainCard.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MainCard
  }
}
</script>

<style lang="scss">
// importo gli stili da common
@import './style/common'
</style>
