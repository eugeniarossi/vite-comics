<script>
export default {
    name: 'AppMainContent',
}
</script>

<template>
    <div id="main-content">
        <div class="container">
            <h2> --> Content goes here</h2>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../../styles/variables.scss' as *;

#main-content {
    background-color: $dark-background-color;
    height: 8.125rem;
    color: #fff;
    .container {
        display: flex;
        align-items: center;
        height: 100%;
    }
}
</style>