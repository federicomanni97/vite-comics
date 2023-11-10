<template>
    <footer>
        <div class="container py-5 d-flex text-light justify-content-between">
            <button class="bg-primary border-0 text-light">SIGN-UP NOW!</button>
            <ul class="d-flex list-unstyled">
                <li>FOLLOW US</li>
                <li><i class="fa-brands fa-facebook-f">1</i></li>
                <li><i class="fa-brands fa-twitter">2</i></li>
                <li><i class="fa-brands fa-youtube">3</i></li>
                <li><i class="fa-brands fa-pinterest-p">4</i></li>
                <li><i class="fa-solid fa-location-dot">5</i></li>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
  name: 'FooterBottom',
  data() {
      

      return {}
  }
}
</script>

<style lang="scss" scoped>
    li{
        padding: 0px 20px;
    }
</style>