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
h1 {
    color: rgb(255, 0, 0);
}

template {
    background-color: aqua;
}
</style>
