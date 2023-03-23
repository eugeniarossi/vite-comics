<script>
export default {
    name: 'AppMainNav',
}
</script>

<template>
    <div id="main-nav">
        <div class="container">
            <nav>
                <ul>
                    <li>
                        <a href="#">
                            <img src="../../img/buy-comics-digital-comics.png" alt="buy">
                            link
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../../img/buy-comics-digital-comics.png" alt="buy">
                            link
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../../img/buy-comics-digital-comics.png" alt="buy">
                            link
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../../img/buy-comics-digital-comics.png" alt="buy">
                            link
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../../img/buy-comics-digital-comics.png" alt="buy">
                            link
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../../styles/variables.scss' as *;

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