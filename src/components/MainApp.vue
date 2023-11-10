<template>
      <main>
        <div class="container text-light">  
            <div class="card" style="width: 18rem;">
                <img class="" :src="image" alt="">
                <div class="">
                    <p class="card-text text-center">{{ text }}</p>
                </div>
            </div> 
        </div>
      </main>
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

</style>