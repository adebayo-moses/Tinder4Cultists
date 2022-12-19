<template>
    <div class="not-found">
        <Header/>
    <div class="container">
            <div class="section-wrapper">
    <div class="zero-item">
                    <div class="zero-thumb">
                        <img src="@/assets/404.png" alt="404" class="center">
                    </div>
                    <div class="zero-content">
                        <h2>Oops! Love for where?</h2>
                        <p>pretty sure your ribs is missing, can't be our page that's missing.  <i class="worried"></i></p>
                        <RouterLink to="/" class="btn-404">Click here to go back to home page<i class="button-double-right"></i></RouterLink>
                    </div>
                </div>
                </div>
                </div>
            </div>
                <footer></footer>
</template>

<script>
import { RouterLink } from 'vue-router'
import header from '@/components/header.vue'
import footer from '@/components/footer.vue'
export default {
    components
    : {
        header,
        footer
    },
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>