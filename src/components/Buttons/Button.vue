<template>
    <button
        @click="clickEvent"
        class="button"
        type="button"
    >
        {{ title }}
    </button>
</template>

<script>
export default {
    name: 'Button',
    props: {
        title: String
    },
    setup(props, { emit }) {
        const title = props.title;
        const clickEvent = () => {
            emit('click-btn', true);
        };
        return {
            clickEvent,
            title
        };
    }
}
</script>

<style lang="scss" scoped>
.button {}
</style>