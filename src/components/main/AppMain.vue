<script>
import AppMainContent from './AppMainContent.vue';
import AppMainNav from './AppMainNav.vue';

export default {
    name: 'AppMain',
    data() {
        return {

        }
    },
    components: {
        AppMainContent,
        AppMainNav
    }
}
</script>

<template>
    <main>
        <AppMainContent></AppMainContent>
        <AppMainNav></AppMainNav>
    </main>
</template>

<style scoped lang="scss"></style>