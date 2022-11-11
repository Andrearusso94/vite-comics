<script>
import comics from '../data/comics.js'
export default {
    name: 'Shop',
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
                <div class="col-2 my-2" v-for="comics in fumetti">
                    <img :src="comics.thumb" :alt="comics.type">
                    <h6 class="my-3">{{ comics.series }}</h6>
                </div>
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


    h6 {
        color: $secondary_color;
        text-transform: uppercase;
        font-size: 0.65rem;
    }

    img {
        width: 150px;
        height: 150px;
    }
}

.btn-container {
    text-align: center;
}

button {
    width: 150px;
}
</style>