<template>
    <div>
        <Header />
<p>This is the about page</p>
<RouterLink to="/">Click here to go back to home page</RouterLink>
    </div>
</template>

<script>
    import Header from '../components/header.vue'
    export default {
        components: {
            Header
        }
    }
</script>
<style lang="scss" scoped>

</style>