<script>
import AppMenu from './AppMenu.vue';
import AppLogoBig from './AppLogoBig.vue';

export default {
    name: 'AppFooterMenu',
    components: {
        AppMenu,
        AppLogoBig
    }
}
</script>

<template>
    <div id="footer-menu">
        <div class="container">
            <AppMenu></AppMenu>
            <AppLogoBig></AppLogoBig>
        </div>
    </div>
</template>

<style scoped lang="scss">
#footer-menu {
    background-image: url('../../assets/img/footer-bg.jpg');
    background-size: cover;
    background-repeat: no-repeat;
}
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
</style>