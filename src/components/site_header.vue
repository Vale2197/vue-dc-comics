<template>
    <header>
        <nav>
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="logoDc">
            </div>
            <!-- LOGO -->
                <ul>
                    <li>
                       <a href="#">CHARACTERS</a>   
                    </li>
                    <li class="active">
                        <a href="#">COMICS</a> 
                    </li>
                    <li>
                        <a href="#">MOVIES</a> 
                    </li>
                    <li>
                        <a href="#">TV</a> 
                    </li>
                    <li>
                        <a href="#">GAMES</a> 
                    </li>
                    <li>
                        <a href="#">COLLECTIBLES</a> 
                    </li>
                    <li>
                        <a href="#">VIDEOS</a> 
                    </li>
                    <li>
                        <a href="#">FANS</a> 
                    </li>
                    <li>
                        <a href="#">NEWS</a> 
                    </li>
                    <li>
                        <a href="#">SHOP</a> 
                    </li>
                </ul>
            <!-- /NAV LINKS -->
        </nav>
    </header>
</template>

<script>
export default {
  name: "site_header"
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    @import '../assets/css_var/colors.scss';

    header {
        background-color: white;
        
        nav {
            width: 80%;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: stretch;
            color: $content_color;
            font-weight: bold;
            background-color: white;
            
            
            ul {
                display: flex;
                list-style-type: none;
                line-height: calc(80px + 2rem);

                li{

                    margin-left: 1rem;

                    a {
                        text-decoration: none;
                        color: $content_color;
                        font-weight: bold;
                        transition: 0.3s;
                        &:hover {
                            color: $logo_color;
                        }
                    }

                    &.active a {
                        color: $logo_color;
                    }

                    &.active {
                        border-bottom: 3px solid $logo_color;
                    }

                }
        
            }
            
            .logo {
                width: 80px;
                padding:  1rem 0;
    
                img {
                    width: 100%;
                }
            }
        }
    }
</style>
