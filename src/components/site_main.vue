<template>
    <main>
        <div class="mainContent">
            <div class="jumbo">
            </div>
            <div class="cards">
                <div class="special">
                    <p>CURRENT SERIES</p>
                </div>
                <card v-for="comic in comics" :key="comic.series" :image="comic.thumb" :description="comic.series"/>

                <div class="loadMore">
                    <p>
                        LOAD MORE
                    </p> 
                </div>
            </div>
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
import card from './card.vue';

    export default {
        
        components: {
            card
        },

        name: "site_main",
        data() {
            return {
                comics: [
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                    },
                    {
                    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                    }
                ]
            }
        }


    }
</script>

<style lang="scss">
    @import '../assets/css_var/colors.scss';
    main {
        background-color: $content_color;
        width: 100%;

        .mainContent {
            margin: auto;
            color: white;
            font-weight: bold;

            .jumbo {
                height: 500px;
                background-image: url("../assets/img/jumbotron.jpg");
                background-repeat: no-repeat;
                background-size: cover;
                background-position: top;
            }

            .cards {
                width: 80%;
                margin: auto;
                display: flex;
                flex-wrap: wrap;
                padding-bottom: 2rem;

                .special {
                    width: 100%;
                    p{
                        height: 3rem;
                        line-height: 3rem;
                        font-size: 1.5rem;
                        width: 16rem;
                        text-align: center;
                        margin-top: -1.5rem;
                        background-color: $shop_nav_color;
                        margin-bottom: 2rem;
                    } 
                }

                .loadMore {
                    width: 100%;
                    text-align: center;

                    p {
                        background-color: $shop_nav_color;
                        width: 12rem;
                        margin: auto;
                        padding: 0.5rem 0;
                    }
                }

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