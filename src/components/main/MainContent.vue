<script>
import MainJumbotron from './MainJumbotron.vue';
import MainSeries from './MainSeries.vue';

export default {
    name: 'MainContent',
    components: {
        MainJumbotron,
        MainSeries
    }
}
</script>

<template>
    <div id="main-content">
        <MainJumbotron></MainJumbotron>
        <MainSeries></MainSeries>
    </div>
</template>

<style scoped lang="scss">
@use 'src/assets/styles/variables.scss' as *;

#main-content {
    background-color: $dark-background-color;
    color: #fff;
}
</style>