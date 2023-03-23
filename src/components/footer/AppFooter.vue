<script>
import AppFooterMenu from './AppFooterMenu.vue';
import AppFooterBottom from './AppFooterBottom.vue';

export default {
    name: 'AppFooter',
    components: {
        AppFooterMenu,
        AppFooterBottom
    }
}
</script>

<template>
    <footer>
        <AppFooterMenu></AppFooterMenu>
        <AppFooterBottom></AppFooterBottom>
    </footer>
</template>

<style scoped lang="scss">
footer {
    display: flex;
    flex-direction: column;
    flex-grow: 1;
}
</style>