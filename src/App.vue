<template>
  <div id="app">
    <header>
      <MyHeader/>
      <MyBanner/>
    </header>

    <main>
      <MainCard/>
      <MyIcon/>
    </main>

    <footer>
      <TheFooter/>
    </footer>
    
  </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue'
import MainCard from './components/MainCard.vue'
import MyIcon from  './components/MyIcon.vue'
import TheFooter from  './components/TheFooter.vue'
import MyBanner from  './components/MyBanner.vue'


export default {
  name: 'App',
  components: {
    MyHeader,
    MainCard,
    MyIcon,
    TheFooter,
    MyBanner
  }
}
</script>

<style lang="scss">
// importo gli stili da common
@import './style/common'
</style>
