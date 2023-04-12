<template>
    <header class="h-50 bg-primary d-flex justify-content-center align-items-center">
        <AppTitle/>
    </header>
</template>

<script>
    import AppTitle from './AppTitle.vue';
    export default {
        name: 'Hero',
        components: {
            AppTitle
        }
    }
</script>

<style lang="scss" scoped>

</style>