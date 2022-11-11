<script>
export default {
    name: 'Jumbo',
}
</script>

<template>
    <div class="jumbo">
        <button class="btn btn-primary">CURRENT SERIES</button>

    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/variables.scss' as *;

.jumbo {
    background-image: url(../assets/img/jumbotron.jpg);
    height: 400px;
    position: relative;

    button {
        position: absolute;
        top: 380px;
        left: 300px;
    }
}
</style>