<script>
import AppLogo from './AppLogo.vue';
import AppHeaderNav from './AppHeaderNav.vue';

export default {
    name: 'AppHeader',
    data() {
        return {

        }
    },
    components: {
        AppLogo,
        AppHeaderNav
    }
}
</script>

<template>
    <header>
        <div class="container">
            <AppLogo></AppLogo>
            <AppHeaderNav></AppHeaderNav>
        </div>
    </header>
</template>

<style scoped lang="scss">
@use 'src/assets/styles/general.scss' as *;

.container {
    @include bar;
}
</style>