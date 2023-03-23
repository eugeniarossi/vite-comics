<script>
export default {
    name: 'AppHeaderNav',
    data() {
        return {
            navLinks: ['characters', 'comics', 'movies', 'tv', 'games', 'collectibles', 'videos', 'fans', 'news', 'shop']
        }
    }
}
</script>

<template>
    <nav>
        <ul>
            <li v-for="link in navLinks">
                <a href="#">{{ link }}</a>
            </li>
        </ul>
    </nav>
</template>

<style scoped lang="scss">
@use '../../styles/variables.scss' as *;

ul {
    display: flex;
    gap: 2.125rem;
    list-style: none;

    li {
        color: $secondary-color;
        height: 7.5rem;

        &:hover {
            color: $primary-color;
            border-bottom: .3125rem solid $primary-color;
        }

        a {
            line-height: 7.5rem;
        }
    }
}
</style>