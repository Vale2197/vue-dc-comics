<template>
    <header>
        <nav>
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="logoDc">
            </div>
            <!-- LOGO -->
                <ul>
                    <li>
                        CHARACTERS  
                    </li>
                    <li class="active">
                        COMICS
                    </li>
                    <li>
                        MOVIES
                    </li>
                    <li>
                        TV
                    </li>
                    <li>
                        GAMES
                    </li>
                    <li>
                        COLLECTIBLES
                    </li>
                    <li>
                        VIDEOS
                    </li>
                    <li>
                        FANS
                    </li>
                    <li>
                        NEWS
                    </li>
                    <li>
                        SHOP
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
    
                li {
                    margin-left: 1rem;

                    &:hover {
                        color: $logo_color;
                    }

                    &.active {
                        color: $logo_color;
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
