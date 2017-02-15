<template>
    <div id="app">
        <navbar></navbar>
        <router-view></router-view>
    </div>
</template>

<script>
    import Navbar from './components/ui/Navbar.vue';

    export default {
        name: 'app',
        components: {
            'navbar': Navbar
        }
    };
</script>

<style>
    body {
        margin-top: 61px !important;
    }

    #app {

    }
</style>
