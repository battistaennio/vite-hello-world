<script>

    export default {
        name: "AppHero"
    }

</script>

<template>

    <div>
        <img src="/public/spiderman.jpg" alt="spiderman">
        <h2>Jumbotron Magnifico</h2>
    </div>

</template>

<style scoped>
    div{
        margin: 0 auto;
        width: 80%;
        height: 20%;
        position: relative;
    }

    img{
        width: 100%;
        border-radius: 25px;
    }

    h2{
        position: absolute;
        top: 50%;
        left: 50%;
        translate: -50% -50%;
        color: white;
        font-size: 50px;
    }
</style>