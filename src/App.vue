<template>
  <div id="app">
    <Header/>
    <Main/>
    <Top/>
    <Middle/>
    <Bottom/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Top from './components/Footer/Top.vue'
import Middle from './components/Footer/Middle.vue'
import Bottom from './components/Footer/Bottom.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Top,
    Middle,
    Bottom
  }
}
</script>

<style lang="scss">
  @import "./assets/style/global.scss";
</style>
