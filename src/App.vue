<template>
  <HeaderApp/>
  <MainApp/>
  <FooterApp/>
</template>

<script>
import HeaderApp from './components/HeaderApp.vue';
import MainApp from './components/MainApp.vue';
import FooterApp from './components/FooterApp.vue';
export default {
  name: 'App',
  components:{
    HeaderApp,
    MainApp,
    FooterApp
  },
  data() {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>

<!-- <ul>
  <li><a href="">Characters</a></li>
  <li><a href="">Comics</a></li>
  <li><a href="">Movies</a></li>
  <li><a href="">Tv</a></li>
  <li><a href="">Games</a></li>
  <li><a href="">Collectibles</a></li>
  <li><a href="">Videos</a></li>
  <li><a href="">Fans</a></li>
  <li><a href="">News</a></li>
  <li><a href="">Shop</a></li>
</ul> -->
