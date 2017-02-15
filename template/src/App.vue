<template>
    <div id="app">
        <app-navbar></app-navbar>
        <router-view></router-view>
        <app-footer></app-footer>
    </div>
</template>

<script>
    import Navbar from './components/ui/Navbar.vue';
    import Footer from './components/ui/Footer.vue';

    export default {
        name: 'app',
        components: {
            'app-navbar': Navbar,
            'app-footer': Footer
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
