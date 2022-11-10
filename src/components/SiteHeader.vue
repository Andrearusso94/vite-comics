<script>
export default {
    name: 'SiteHeader',
    data() {
        return {
            menu: [
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
                    text: 'Collectibles',
                    href: '#',
                },
                {
                    text: 'Video',
                    href: '#',
                },
                {
                    text: 'Fans',
                    href: '#',
                },
                {
                    text: 'News',
                    href: '#',
                },
                {
                    text: 'Shop',
                    href: '#',
                }
            ]
        }
    }
}
</script>
<template>
    <header id="site-header">
        <div class="container">
            <nav class="navbar navbar-expand-lg navbar-light  bg-light">
                <img src="../assets/img/dc-logo.png" alt="" class="my-2">

                <div class="collapse navbar-collapse justify-content-end" id="navbarText">
                    <ul class="navbar-nav">
                        <li v-for="item in menu" class="nav-item active">

                            <a class="nav-link text-dark" :href="item.href">{{ item.text }}</a>
                        </li>

                    </ul>
                </div>
            </nav>
        </div>



    </header>
</template>

<style lang="scss" scoped>

</style>