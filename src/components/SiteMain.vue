<script>
export default {
    name: 'SiteMain',
    data() {
        return {
            menu: [
                {
                    text: 'Digital Comics',
                    img: '../assets/img/buy-comics-digital-comics.png',
                    href: '#',
                },
                {
                    text: 'DC merchandise',
                    img: '../assets/img/buy-comics-merchandise.png',
                    href: '#',
                },
                {
                    text: 'subscription',
                    img: '../assets/img/buy-comics-subscription.png',
                    href: '#',
                },
                {
                    text: 'comic shop locator',
                    img: '../assets/img/buy-comics-shop-locator.png',
                    href: '#',
                },
                {
                    text: 'dc power visa',
                    img: '../assets/img/buy-dc-power-visa.svg',
                    href: '#',
                },
            ]
        }
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
        <div class="container_secondary">
            <div class="container">
                <div class="row justify-content-around">
                    <div v-for="item in menu" class="col-2">
                        <img :src="item.img" alt="">

                        <a :href="item.href">{{ item.text }}</a>
                    </div>

                </div>

            </div>
        </div>



    </main>
</template>

<style lang="scss" scoped>

</style>