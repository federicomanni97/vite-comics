<template>
  <div class="container">
    <HeaderApp/>
  </div>  
  <div class="jumbotron-bg w-100">
  </div>
  <div class="bg-dark">
    <div class="container">
      <span class="fs-3 py-3 px-5 bg-primary text-uppercase text-light">Current Series</span>
      <div class="row py-4">
        <MainApp v-for="card in array"
        :image="card.thumb"
        :text="card.series"
        />
      </div>
      <div class="text-center">
        <button class="bg-primary py-2 px-5 my-4 border-0 text-light">LOAD MORE</button>
      </div>  
    </div>
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
import MainBottom from './components/MainBottom.vue';
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
    return {
            array:[
        {
            "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
            "price": "$19.99",
            "series": "Action Comics",
            "type": "comic book",
        },
        {
            "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
            "price": "$3.99",
            "series": "American Vampire 1976",
            "type": "comic book",
        },
        {
            "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
            "price": "$16.99",
            "series": "Aquaman",
            "type": "graphic novel",
        },
        {
            "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
            "price": "$2.99",
            "series": "Batgirl",
            "type": "comic book",
        },
        {
            "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
            "price": "$3.99",
            "series": "Batman",
            "type": "comic book",
        },
        {
            "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
            "price": "$2.99",
            "series": "Batman Beyond",
            "type": "comic book",
        },
        {
            "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
            "price": "$3.99",
            "series": "Batman/Superman",
            "type": "comic book",
        },
        {
            "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
            "price": "$4.99",
            "series": "Batman/Superman Annual",
            "type": "comic book",
        },
        {
            "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
            "price": "$5.99",
            "series": "Batman: The Joker War Zone",
            "type": "comic book",
        },
        {
            "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
            "price": "$6.99",
            "series": "Batman: Three Jokers",
            "type": "comic book",
        },
        {
            "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
            "price": "$4.99",
            "series": "Batman: White Knight Presents: Harley Quinn",
            "type": "comic book",
        },
        {
            "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
            "price": "$16.99",
            "series": "Catwoman",
            "type": "graphic novel",
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
  .top-footer{
    background-image: url(img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover; 
  }
  
  .jumbotron-bg{
    background-image: url(img/jumbotron.jpg);
    background-size: cover;
    height: 400px;
  }
  


  .bg-ciao{
    background-color: #303030;
  }
</style>
