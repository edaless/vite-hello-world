<script>
export default {
    name: "AppTitle",
    data() {
        return {
            saluto: "La mia prima app con Vite!"
        }
    }
}
</script>

<template>

    <!-- <h1>Ciaoooo</h1> -->
    <h2>{{ saluto }}</h2>


</template>

<style scoped>
body {
    background-color: aqua;
}

h2 {
    background-color: brown;
    width: 100vw;
}
</style>
