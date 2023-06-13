<template>
    <div class="container">
        <Header />
        <main class="main">
            <slot></slot>
        </main>
        <Footer />
    </div>
</template>

<script>
import Header from '../components/TemplateComponents/Header/Header.vue';
import Footer from '../components/TemplateComponents/Footer/Footer.vue';
export default {
    name: 'Template',
    components: {
        Header,
        Footer
    }
}
</script>

<style lang="scss" scoped>
.container {}
</style>