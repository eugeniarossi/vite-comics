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
        <AppLogo></AppLogo>
        <AppHeaderNav></AppHeaderNav>
    </header>
</template>

<style scoped lang="scss">
@use '../../styles/general.scss' as *;
@use '../../styles/variables.scss' as *;


</style>