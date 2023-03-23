<script>
import AppLink from './AppLink.vue';
import AppFooterNav from './AppFooterNav.vue';

export default {
    name: 'AppFooterBottom',
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
    <div id="footer-bottom">
        <div class="container">
            <AppLink></AppLink>
            <AppFooterNav></AppFooterNav>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../../styles/variables.scss' as *;
@use '../../styles/general.scss' as *;

#footer-bottom {
    height: 6.875rem;
    background-color: $background-color;
}

.container {
    @include bar;
}
</style>