<script>
import Banner from './Banner.vue'
export default {
    name: 'SiteMain',

    components: {
        Banner,
    }

}
</script>
<template>
    <main id="site-main">
        <div class="container_primary">
            <div class="container">
                <h3 class="py-5">--> Content goes here </h3>
            </div>
        </div>
        <Banner></Banner>



    </main>
</template>

<style lang="scss" scoped>

</style>