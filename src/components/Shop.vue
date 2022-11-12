<script>
import comics from '../data/comics.js'
import ShopComic from './ShopComic.vue'
export default {
    name: 'Shop',
    components: {
        ShopComic
    },
    data() {
        return {
            fumetti: comics
        }
    }
}
</script>

<template>
    <div class="container_primary p-5">
        <div class="container">
            <div class="row">
                <ShopComic v-for="comics in fumetti" :thumb="comics.thumb" :series="comics.series" />

                <div class="btn-container container my-2">
                    <button class="btn btn-primary">LOAD MORE</button>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/variables.scss' as *;

.container_primary {
    background-color: $dark;
}

.btn-container {
    text-align: center;
}

button {
    width: 150px;
}
</style>