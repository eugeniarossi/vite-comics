<script>
export default {
    name: 'AppFooterNav',
    data() {
        return {
            footerNavLinks: ['src/assets/img/footer-facebook.png', 'src/assets/img/footer-twitter.png', 'src/assets/img/footer-youtube.png', 'src/assets/img/footer-pinterest.png', 'src/assets/img/footer-periscope.png']
        }
    }
}
</script>

<template>
    <nav>
        <h2>follow us</h2>
        <ul>
            <li v-for="link in footerNavLinks">
                <a href="#">
                    <img :src="link" alt="social">
                </a>
            </li>
        </ul>
    </nav>
</template>

<style scoped lang="scss">
@use 'src/assets/styles/variables.scss' as *;

nav {
    display: flex;
    align-items: center;
    gap: 1.875rem;

    h2 {
        color: $primary-color;
    }

    ul {
        display: flex;
        gap: 1.25rem;
        list-style: none;

        li {
            a {
                text-decoration: none;
            }
        }
    }
}
</style>