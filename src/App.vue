<template>
  <div class="container">
    <HeaderApp/>
    <MainApp/>
    <MainBottom/>
    <FooterTop/>
    <FooterBottom/>
  </div>
</template>

<script>
import HeaderApp from './components/HeaderApp.vue';
import MainApp from './components/MainApp.vue';
import MainBottom from './components/MainBottom.vue'
import FooterTop from './components/FooterTop.vue';
import FooterBottom from './components/FooterBottom.vue';
export default {
  name: 'App',
  components:{
    HeaderApp,
    MainApp,
    MainBottom,
    FooterTop,
    FooterBottom
  },
  data() {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>
