<template>
    <div class="bg-primary text-light d-flex align-items-center justify-content-between p-5">
        <div v-for="element in mainBottom">
            <img :src="element.img" alt="">
            <span class="p-3">{{ element.text }}</span>
        </div>
    </div>
</template>
<script>
export default {
    name: 'MainBottom',
    setup () {
        

        return {
            mainBottom: [
                {
                    img: '../../public/img/buy-comics-digital-comics.png',
                    text: 'Digital Comics'
                },
                {
                    img: '/public/img/buy-comics-merchandise.png',
                    text: 'DC Merchandise'
                },
                {
                    img: '/public/img/buy-comics-subscriptions.png',
                    text: 'Subscription'
                },
                {
                    img: '/public/img/buy-comics-shop-locator.png',
                    text: 'Comic Shop Locator'
                },
                {
                    img: '/public/img/buy-dc-power-visa.svg',
                    text: 'DC Power Visa'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.ciao{
    background-color: black;
    color: white;
}
img{
    width: 40px;
}

</style>