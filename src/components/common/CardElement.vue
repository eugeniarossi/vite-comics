<script>
export default {
    name: 'CardElement',
    props: {
        img: String,
        title: String
    },

}
</script>

<template>
    <div class="card">
        <div class="image">
            <img :src="img" alt="{{ title }}">
        </div>
        <div class="title">
            <h5>{{ title }}</h5>
        </div>
    </div>
</template>

<style scoped lang="scss">
</style>