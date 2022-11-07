<script>
export default {
    data () {
        return {
            jumboText: "Questo è il mio primo jumbotron in Vue + Vite"
        }
    }
}
</script>

<template>
    <div class="jumbotron">
        <span class="jt-text">{{jumboText}}</span>
    </div>
</template>

<style scoped>
    .jumbotron {
        width: 100%;
        height: 500px;
        background-image: url("../assets/pizza_pexels.jpg");
        background-size: cover;
        background-position: center;
        padding: 1.5rem
    }

    .jt-text {
        display: block;
        text-align: end;
        font-size: 3rem;
        color: white;
        text-shadow: 2px 2px black;
    }
</style>