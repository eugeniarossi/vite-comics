<script>
import MainContent from './MainContent.vue';
import MainNav from './MainNav.vue';

export default {
    name: 'AppMain',
    data() {
        return {

        }
    },
    components: {
        MainContent,
        MainNav
    }
}
</script>

<template>
    <main>
        <MainContent></MainContent>
        <MainNav></MainNav>
    </main>
</template>

<style scoped lang="scss"></style>