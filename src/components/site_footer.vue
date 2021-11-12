<template>
    <footer>
        <section class="foot_links">
            <div class="row">
                <div class="col-2">
                    <h2>
                        DC COMICS
                    </h2>
                    <ul>
                        <li>
                           <a href="#">Character</a> 
                        </li>
                        <!--  -->

                        <li>
                           <a href="#">Comics</a> 
                        </li>
                        <!--  -->

                        <li>
                           <a href="#">Movies</a> 
                        </li>
                        <!--  -->

                        <li>
                           <a href="#">TV</a> 
                        </li>
                        <!--  -->

                        <li>
                           <a href="#">Games</a> 
                        </li>
                        <!--  -->

                        <li>
                           <a href="#">Videos</a> 
                        </li>
                        <!--  -->

                        <li>
                           <a href="#">News</a> 
                        </li>
                        <!--  -->
                    </ul>

                    <div class="col">
                        <h2>
                            SHOP
                        </h2>
                        <ul>
                            <li>
                                <a href="#">Shop DC</a>
                            </li>
                            <!--  -->
    
                            <li>
                                <a href="#">Shop DC Collectibles</a>
                            </li>
                            <!--  -->
                        </ul>
                    </div>
                    <!-- /SHOP -->
                </div>
                <!-- /DC COMICS -->

                <div class="col-2">
                    <h2>
                        DC
                    </h2>
                    <ul>
                        <li>
                            <a href="#">Terms of use</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">Privacy policy(New)</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">Ad Choices</a>  
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">Advertising</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">Jobs</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">Subscriptions</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">Talent Workshop</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">CPSC Certificates</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">Ratings</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">Shop help</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">Contact us</a> 
                        </li>
                        <!--  -->
                    </ul>
                </div>
                <!-- /DC -->

                <div class="col-2">
                    <h2>
                        SITES
                    </h2>
                    <ul>
                        <li>
                            <a href="#">DC</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">MAD Magazine</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">DC Kids</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">DC Universe</a> 
                        </li>
                        <!--  -->

                        <li>
                            <a href="#">DC Power Visa</a> 
                        </li>
                        <!--  -->
                    </ul>
                </div>
                <!-- //SITES -->
            </div>
        </section>
        <!-- //section links -->

        <section class="follow_us">

            <div class="container">

                <div class="sign_up">
                    <p>
                        SIGN-UP NOW!
                    </p>
                </div>
                <div class="follow">
                    <P>
                        FOLLOW US
                    </P>
                    <img src="../assets/img/footer-facebook.png" alt="#">
                    <img src="../assets/img/footer-twitter.png" alt="#">
                    <img src="../assets/img/footer-youtube.png" alt="#">
                    <img src="../assets/img/footer-pinterest.png" alt="#">
                    <img src="../assets/img/footer-periscope.png" alt="#">
                </div>

            </div>

        </section>
    </footer>
</template>

<script>
    export default {
        name: "site_footer"
    }
</script>

<style lang="scss">
    @import "../assets/css_var/colors.scss";
    footer {
        font-weight: bold;
        background-image: url("../assets/img/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: top;
        .foot_links {
            width: 80%;
            margin: auto;
            padding: 3rem 0;
            background-image: url("../assets/img/dc-logo-bg.png");
            background-size: 500px;
            background-position: right;
            background-repeat: no-repeat;

            .row {
                display: flex;
                flex-wrap: wrap;

                .col-2 {
                    width: calc((100% / 12) * 2);
                    margin-top: 1rem;

                    .col {
                        width: 100%;
                        margin-top: 1rem;
                    }
                }

                ul {
                    list-style-type: none;
                    margin-top: 1rem;

                    a {
                        text-decoration: none;
                        color: $footer_font_color;
                        transition: 0.3s;

                        &:hover {
                            color: white;
                        }
                    }
                }

                h2 {
                    color: white;
                }

            }
        }

        .follow_us {
            background-color: $sign_up_sectionColor;
            padding: 2rem 0;
            .container {
                width: 80%;
                margin: auto;
                display: flex;
                justify-content: space-between;
                align-items: center;

                .follow {
                    display: flex;
                    align-items: center;
                    color: $shop_nav_color;

                    img {
                        margin-left: 1rem;
                    }
                }

                .sign_up {
                    color: white;
                    font-weight: bold;

                    p {
                        border: 2px solid $shop_nav_color;
                        padding: 0.5rem;
                        border-radius: 0.3rem;
                    }
                }
            }
        }

    }
</style>