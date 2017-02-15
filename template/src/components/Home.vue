<template>
    <div class="home">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
    export default {
        name: 'home',
        data() {
            return {
                msg: 'Saluton Mondo'
            }
        }
    }
</script>

<style scoped>
    h1 {
        color: darkslateblue;
    }
</style>
