<script>
export default {
    name: 'AppHeaderNav',
    data() {
        return {

        }
    }
}
</script>

<template>
    <nav>
        <ul>
            <li>
                <a href="#">character</a>
            </li>
            <li>
                <a href="#">character</a>
            </li>
            <li>
                <a href="#">character</a>
            </li>
            <li>
                <a href="#">character</a>
            </li>
            <li>
                <a href="#">character</a>
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
            text-decoration: none;
            line-height: 7.5rem;
        }
    }
}
</style>