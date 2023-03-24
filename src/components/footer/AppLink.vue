<script>
export default {
    name: 'AppLink',
    data() {
        return {

        }
    }
}
</script>

<template>
    <a href="#">
        sign-up now!
    </a>
</template>

<style scoped lang="scss">
@use 'src/assets/styles/variables.scss' as *;

a {
    color: #fff;
    padding: .625rem .8125rem;
    border: .125rem solid $primary-color;
}
</style>