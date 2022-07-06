<template>
  <div id="app">
    <header>
      <MyHeader/>
    </header>

    <main>
      <MainCard/>
      <MyIcon/>
    </main>
    
  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MainCard from './components/MainCard.vue'
import MyIcon from  './components/MyIcon.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MainCard,
    MyIcon
  }
}
</script>

<style lang="scss">
// importo gli stili da common
@import './style/common'
</style>
