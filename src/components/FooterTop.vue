<template>
    <footer>
        <div class="container d-flex justify-content-between py-3 text-light position-">
            <div class="flex-column">
                <div class="px-3">
                    <h5>DC COMICS</h5>
                    <ul class="p-0 ">
                        <li v-for="list in first"><a href="">{{ list }}</a></li>
                    </ul>
                </div>
                <div class="px-3">
                    <h5>SHOP</h5>
                    <ul class="p-0">
                        <li v-for="list in fourth"><a href="">{{ list }}</a></li>
                    </ul>
                </div>
            </div>
            <div class="px-3">
                <h5>DC</h5>
                <ul class="p-0">
                    <li v-for="list in second"><a href="">{{ list }}</a></li>
                </ul>
            </div>
            <div class="px-3"> 
                <h5>SITES</h5>
                <ul class="p-0">
                    <li v-for="list in third"><a href="">{{ list }}</a></li>
                </ul>
            </div>
            <div class="right-logo">
                <img src="img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </footer>
</template>

<script>
export default {
  name: 'FooterTop',
  data() {
      
      return {
                first: [
                    'Characters',
                    'Comics',
                    'Movies',
                    'Tv',
                    'Games',
                    'Videos',
                    'News'
                ],
                second: [
                    'Shop DC',
                    'Shop DC Collectibles'
                ],
                third: [
                    'Terms of Use',
                    'Privacy Policy (New)',
                    'Ad Choices',
                    'Advertising',
                    'Jobs',
                    'Subscriptions',
                    'Talent Workshops',
                    'CPSC Certificates',
                    'Ratings',
                    'Shop Help',
                    'Contact Us'
                ],
                fourth: [
                    'DC',
                    'MAD Magazine',
                    'DC Kids',
                    'DC Universe',
                    'DC Power Visa',
                ]
      }
  }
}
</script>

<style lang="scss" scoped>
    ul {
    list-style: none;
    }
    a{
        text-decoration: none; 
        color: grey;
    }
</style>