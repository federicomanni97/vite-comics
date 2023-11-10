<template>
        <div class="col-2 py-4">
                <img class="" :src="image" alt="">
                <span class="text-light text-uppercase fs-6">{{ text }}</span>
        </div>
</template>

<script>
export default {
    name: 'MainApp',
    props: {
        image: String,
        text: String,
    },
    data() {
        return {}
    }
}
</script>

<style lang="scss" scoped>
    img{
        height: 200px;
        width: 200px;
        object-fit: cover;
    }


</style>