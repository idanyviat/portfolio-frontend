<template>
    <header class="header">
        <div class="container">
            <section class="header__logo">MNTN</section>
            <section class="header__navigate">
                <a href="#" class="header__link">Каталог</a>
                <a href="#" class="header__link">Компитенции</a>
                <a href="#" class="header__link">Контакты</a>
            </section>
            <section class="header__account">
                <button type="button">Account</button>
            </section>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style lang="scss" scoped>
.header {
    display: flex;
    justify-content: center;
    width: 100%;
    height: 60px;

    .container {
        display: flex;
        justify-content: space-between;
    }
}
</style>