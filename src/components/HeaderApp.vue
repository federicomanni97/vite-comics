<template>
        <div class="d-flex justify-content-between align-items-center">
        <img src="/public/img/dc-logo.png" alt="Logo">
        <div>
            <NavbarApp/>
        </div>
        </div>
</template>

<script>
import NavbarApp from './Nav/NavbarApp.vue'
export default {
    name: 'HeaderApp',
    components: {
        NavbarApp
    },
    data() {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>