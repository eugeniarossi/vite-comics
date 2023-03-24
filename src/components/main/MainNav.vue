<script>
export default {
    name: 'MainNav',
    data() {
        return {
            mainNavLinks: [
                {
                    src: '../../assets/img/buy-comics-digital-comics.png',
                    name: 'digital comics'
                }, {
                    src: '../../assets/img/buy-comics-merchandise.png',
                    name: 'dc merchandise'
                }, {
                    src: '../../assets/img/buy-comics-subscriptions.png',
                    name: 'subscription'
                }, {
                    src: '../../assets/img/buy-comics-shop-locator.png',
                    name: 'comic shop locator'
                }, {
                    src: '../../assets/img/buy-dc-power-visa.svg',
                    name: 'dc power visa'
                }
            ]
        }
    }
}
</script>

<template>
    <div id="main-nav">
        <div class="container">
            <nav>
                <ul>
                    <li v-for="link in mainNavLinks">
                        <a href="#">
                            <img :src="link.src" alt="buy">
                            <div>{{ link.name }}</div>
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use 'src/assets/styles/variables.scss' as *;

#main-nav {
    background-color: $primary-color;
    height: 9.375rem;
    display: flex;
    align-items: center;

    nav {
        ul {
            display: flex;
            gap: 4.5625rem;
            list-style: none;
            text-transform: uppercase;

            li {
                a {
                    text-decoration: none;
                    color: #fff;
                    display: flex;
                    align-items: center;
                    gap: 1rem;

                    img {
                        height: 3.4375rem;
                    }
                }
            }
        }
    }
}
</style>