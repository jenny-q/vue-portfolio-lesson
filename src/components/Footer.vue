<template>
    <footer class="footer bg-light">
            <p>&copy; {{footerDate()}} Jennifer Quispe. All rights reserved.</p>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
    methods: {
        footerDate() {
            return new Date().getFullYear();
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
    padding: 1rem 0;
    font-size:.85rem;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: auto;
}
</style>
