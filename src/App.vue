<script>
import AppHeader from './components/header/AppHeader.vue';
import AppMain from './components/main/AppMain.vue';
import AppFooter from './components/footer/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/variables.scss' as *;

.container {
  @include container;
}

header {
  height: 7.5rem;
}

main {
  background-color: pink;
  flex-grow: 1;
}

footer {
  height: 6.875rem;
  background-color: $background-color;
}
</style>
