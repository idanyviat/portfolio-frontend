<template>
    <Header />
    <div class="container">
        <slot></slot>
    </div>
    <Footer />
</template>

<script>
import Header from '../components/Header/Header.vue';
import Footer from '../components/Footer/Footer.vue';

export default {
    name: 'Layout',
    components: {
        Header,
        Footer
    }
}
</script>

<style scoped></style>