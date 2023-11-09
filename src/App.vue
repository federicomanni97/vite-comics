<template>
  <div class="container">
    <HeaderApp/>
  </div>  
  <div class="bg-dark">
    <MainApp/>
  </div>  
  <div class="bg-primary">
    <MainBottom/>
  </div>
  <div class="top-footer">
    <FooterTop/>
  </div>  
  <div class="bg-ciao">
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
  .top-footer{
    background-image: url(img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover; 
  }

  .bg-ciao{
    background-color: #303030;
  }
</style>
