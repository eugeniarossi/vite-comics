<script>
export default {
    name: 'AppMenu',
}
</script>

<template>
    <div id="menu">
        <div class="menu-section">
            <h3>DC COMICS</h3>
            <ul>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>

            </ul>
            <h3>SHOP</h3>
            <ul>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>

            </ul>
        </div>

        <div class="menu-section">
            <h3>DC</h3>
            <ul>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>

            </ul>
        </div>

        <div class="menu-section">
            <h3>SITES</h3>
            <ul>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                <li>
                    <small>
                        <a href="#">Characters</a>
                    </small>
                </li>
                
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
#menu {
    display: flex;
    flex-grow: 1;
    gap: 2rem;
    color: #fff;

    .menu-section {
        h3 {
            margin-bottom: .625rem;
        }

        ul {
            margin-bottom: 1rem;
            font-size: small;
            color: #959595;
        }
    }
}
</style>