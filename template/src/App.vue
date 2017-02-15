<template>
    <div id="app">
        <app-navbar></app-navbar>
        <router-view></router-view>
        <app-footer></app-footer>
    </div>
</template>

<script>
    import jQuery from 'jquery';
    import Navbar from './components/ui/Navbar.vue';
    import Footer from './components/ui/Footer.vue';

    // Make jQuery available to the entire page
    // TODO: Improve this or remove jQuery
    const $ = window.$ = window.jQuery = jQuery;

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
