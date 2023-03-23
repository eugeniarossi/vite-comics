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

ul {
    display: flex;
    gap: 2.125rem;
    list-style: none;

    li {
        a {
            text-decoration: none;
        }
    }
}
</style>