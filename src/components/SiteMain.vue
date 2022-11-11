<script>
import Banner from './Banner.vue'
import Jumbo from './Jumbo.vue'
import Shop from './Shop.vue'
export default {
    name: 'SiteMain',

    components: {
        Banner,
        Jumbo,
        Shop,
    }

}
</script>
<template>
    <main id="site-main">
        <Jumbo></Jumbo>
        <Shop></Shop>
        <Banner></Banner>



    </main>
</template>

<style lang="scss" scoped>

</style>