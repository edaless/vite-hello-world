<script>
export default {

    data() {
        return {
            saluto: "Hero"
        }
    }
}
</script>

<template>


    <h2>{{ saluto }}</h2>
    <img src="https://www.tuttogreen.it/wp-content/uploads/2020/03/shutterstock_120544951.jpg" alt="">


</template>

<style scoped>
h2 {
    color: rgb(255, 0, 0);
}

img {
    width: 100vw;
    height: auto;
}
</style>
