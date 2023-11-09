<template>
        <ul class="d-flex list-unstyled py-5">
            <li v-for="navs in navBar"><a href="">{{navs}}</a></li>
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