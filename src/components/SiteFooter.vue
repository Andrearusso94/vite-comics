<script>
export default {
    name: 'SiteFooter',
    data() {
        return {
            linkMenu: [
                {
                    text: 'Charaters',
                    href: '#',
                },
                {
                    text: 'Comics',
                    href: '#',
                },
                {
                    text: 'Movies',
                    href: '#',
                },
                {
                    text: 'Tv',
                    href: '#',
                },
                {
                    text: 'Games',
                    href: '#',
                },
                {
                    text: 'Videos',
                    href: '#',
                },
                {
                    text: 'News',
                    href: '#',
                },
            ],
            shop: [
                {
                    text: 'Shop DC',
                    href: '#',
                },
                {
                    text: 'Shop DC Collectibles',
                    href: '#',
                },
            ],
            dcMenu: [
                {
                    text: 'Terms Of Use',
                    href: '#',
                },
                {
                    text: 'Privacy policy (New)',
                    href: '#',
                },
                {
                    text: 'Ad Choise',
                    href: '#',
                },
                {
                    text: 'Advertising',
                    href: '#',
                },
                {
                    text: 'Jobs',
                    href: '#',
                },
                {
                    text: 'Subscription',
                    href: '#',
                },
                {
                    text: 'Talent Workshops',
                    href: '#',
                },
                {
                    text: 'CPSC Certificates',
                    href: '#',
                },
                {
                    text: 'Ratings',
                    href: '#',
                },
                {
                    text: 'Shop Help',
                    href: '#',
                },
                {
                    text: 'Contact Us',
                    href: '#',
                },

            ],
            sites: [
                {
                    text: 'DC',
                    href: '#',
                },
                {
                    text: 'MAD Magazine',
                    href: '#',
                },
                {
                    text: 'DC kids',
                    href: '#',
                },
                {
                    text: 'DC Universe',
                    href: '#',
                },
                {
                    text: 'DC Power Visa',
                    href: '#',
                },
            ]
        }
    }
}
</script>
<template>
    <footer id="site-footer">
        <div class="container_link">
            <div class="container footer-top py-5">
                <div class="row">
                    <div class="col-2">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li v-for="item in linkMenu">
                                <a :href="item.href">{{ item.text }}</a>
                            </li>
                        </ul>
                        <h3 class="my-2">Shop</h3>
                        <ul class="my-2">
                            <li v-for="item in shop">
                                <a :href="item.href">{{ item.text }}</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col-2">
                        <h3>DC</h3>
                        <ul>
                            <li v-for="item in dcMenu">
                                <a :href="item.href">{{ item.text }}</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col-2">
                        <h3>Sites</h3>
                        <ul>
                            <li v-for="item in sites">
                                <a :href="item.href">{{ item.text }}</a>
                            </li>

                        </ul>
                    </div>
                    <div class="col-6">
                        <img src="../assets/img/dc-logo-bg.png" alt="">
                    </div>
                </div>
            </div>
        </div>

        <div class="container_social">
            <div class="container d-flex  justify-content-between">
                <div class="shop">
                    <button class="my-5">Sign-Up Now!</button>
                </div>

                <div class="social my-5 d-flex">
                    <h3 class="mx-2">FOLLOW US</h3>
                    <img class="mx-2" src="../assets/img/footer-facebook.png" alt="">
                    <img class="mx-2" src="../assets/img/footer-twitter.png" alt="">
                    <img class="mx-2" src="../assets/img/footer-youtube.png" alt="">
                    <img class="mx-2" src="../assets/img/footer-pinterest.png" alt="">
                    <img class="mx-2" src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>>


        </div>
    </footer>
</template>

<style lang="scss" scoped>

</style>