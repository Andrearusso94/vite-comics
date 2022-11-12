<script>
export default {
    props: {
        thumb: String,
        series: String,
    }

}
</script>

<template>

    <div class="col-2 my-2">
        <img :src="thumb" :alt="type">
        <h6 class="my-3">{{ series }}</h6>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/variables.scss' as *;




h6 {
    color: $secondary_color;
    text-transform: uppercase;
    font-size: 0.65rem;
}

img {
    width: 150px;
    height: 150px;
}
</style>
