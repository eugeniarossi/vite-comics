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
    <footer>
        <div class="container">
            <AppLink></AppLink>
            <AppFooterNav></AppFooterNav>
        </div>
    </footer>
</template>

<style scoped lang="scss">
@use '../../styles/general.scss' as *;

.container {
    @include bar;
}
</style>