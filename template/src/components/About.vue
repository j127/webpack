<template>
    <div class="about">
        <h1>{{ msg }}</h1>
        <p>This is the about page.</p>
    </div>
</template>

<script>
    export default {
        name: 'about',
        data() {
            return {
                msg: 'About'
            }
        }
    };
</script>

<style scoped>
    h1 {
        color: darkslateblue;
    }
</style>
