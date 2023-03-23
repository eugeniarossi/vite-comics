<script>
import AppLink from './AppLink.vue';
import AppNav from './AppNav.vue';

export default {
    name: 'AppNavbar',
    data() {
        return {

        }
    },
    components: {
        AppLink,
        AppNav
    }
}
</script>

<template>
     <div id="navbar">
        <AppLink></AppLink>
        <AppNav></AppNav>
    </div>
</template>

<style scoped lang="scss">
#navbar {
    display: flex;
    justify-content: space-between;
}</style>