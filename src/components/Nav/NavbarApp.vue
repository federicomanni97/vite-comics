<template>
        <ul class="d-flex list-unstyled py-5">
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
        </ul>
</template>

<script>
export default {
    name: 'NavbarApp',
    data() {
        

        return {
            navBar: [
            'Characters',
            'Comics',
            'Movies',
            'Tv',
            'Games',
            'Collectibles',
            'Videos',
            'Fans',
            'News',
            'Shop'
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    li{
        padding: 0px 10px;
    }
    a{
        text-decoration: none; 
        color: black;
    }

</style>