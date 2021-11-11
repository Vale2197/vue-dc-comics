<template>
    <main>
        <div class="mainContent">
            <p>
                CONTENTS HERE
            </p>
            <!-- / comics section -->

            <div class="shop-sections">

                <ul>
                    <li>
                        <div class="img">
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="#">
                        </div>
                        <a href="#">
                            DIGITAL COMICS
                        </a>
                    </li>
                    <!-- //LIST ITEM -->

                    <li>
                        <div class="img">
                            <img src="../assets/img/buy-comics-merchandise.png" alt="#">
                        </div>
                        <a href="#">
                            DC MARCHANDISE
                        </a>
                    </li>
                    <!-- //LIST ITEM -->

                    <li>
                        <div class="img">
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="#">
                        </div>
                        <a href="#">
                            SUBSCRIPTION
                        </a>
                    </li>
                    <!-- //LIST ITEM -->

                    <li>
                        <div class="img">
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="#">
                        </div>
                        <a href="#">
                            COMIC SHOP LOCATOR
                        </a>
                    </li>
                    <!-- //LIST ITEM -->

                    <li>
                        <div class="img">
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="#">
                        </div>
                        <a href="#">
                            DC POWER VISA
                        </a>
                    </li>
                    <!-- //LIST ITEM -->

                </ul>

            </div>
            <!-- //SHOP SECTION -->
        </div>
        
    </main>
</template>

<script>
    export default {
        name: "site_main"
    }
</script>

<style scoped lang="scss">
    @import '../assets/css_var/colors.scss';
    main {
        background-color: $content_color;
        width: 100%;

        .mainContent {
            margin: auto;
            color: white;
            font-weight: bold;

            p {
                font-size: 2rem;
                width: 80%;
                margin: auto;
                padding: 3rem 0;
            }

            .shop-sections {
                    background-color: $shop_nav_color;
                    padding: 3rem 0;
                ul {
                    width: 80%;
                    margin: auto;
                    display: flex;
                    justify-content: space-around;

                    li {
                        display: flex;
                        align-items: center;

                        .img {
                            width: 60px;

                            img {
                                width: 100%;
                            }
                        }

                        a {
                            color: white;
                            text-decoration: none;
                            font-weight: bold;
                            padding-left: 1rem;
                        }
                    }
                }
            }
        }
    }
</style>