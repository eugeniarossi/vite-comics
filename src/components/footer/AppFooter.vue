<script>
import AppLink from './AppLink.vue';
import AppFooterNav from './AppFooterNav.vue';

export default {
    name: 'AppFooter',
    data() {
        return {
            
        }
    },
    components: {
       AppLink,
       AppFooterNav
    }
}
</script>

<template>
    <AppLink></AppLink>
    <AppFooterNav></AppFooterNav>
</template>

<style scoped lang="scss">

</style>