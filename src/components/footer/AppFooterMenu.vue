<script>
import AppMenu from '../main/AppMenu.vue';
import AppLogoBig from '../main/AppLogoBig.vue';

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
@use '../../styles/variables.scss' as *;

#footer-menu {
    background-image: url('../../img/footer-bg.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
}
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
}
</style>