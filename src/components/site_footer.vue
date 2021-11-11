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
        <section class="follow_us"></section>
    </footer>
</template>

<script>
    export default {
        name: "site_footer"
    }
</script>

<style scoped lang="scss">
    footer {
        font-weight: bold;

        .foot_links {
            width: 80%;
            margin: auto;

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
                    }
                }

            }
        }
    }
</style>