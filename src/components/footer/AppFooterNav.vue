<script>
export default {
    name: 'AppFooterNav',
    data() {
        return {

        }
    }
}
</script>

<template>
    <nav>
        <h2>follow us</h2>
        <ul>
            <li>
                <a href="#">
                    <img src="../../img/footer-facebook.png" alt="facebook logo">
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../../img/footer-facebook.png" alt="facebook logo">
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../../img/footer-facebook.png" alt="facebook logo">
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../../img/footer-facebook.png" alt="facebook logo">
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../../img/footer-facebook.png" alt="facebook logo">
                </a>
            </li>
        </ul>
    </nav>
</template>

<style scoped lang="scss">
@use '../../styles/variables.scss' as *;

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