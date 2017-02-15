<template>
    <footer>
        Copyright &copy; {{ currentYear }}
    </footer>
</template>

<script>
    export default {
        computed: {
            currentYear: () => {
                new Date().getFullYear();
            }
        }
    }
</script>

<style scoped>
    footer {
        color: #ccc;
    }
</style>
