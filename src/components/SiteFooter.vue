<template>
    <footer id="site_footer">
        <div class="footer_links">
            <div class="container">
                <div class="row d_flex">
                    <div class="col">
                    <h2>DC Comics</h2>
                    <ul>
                        <li><a href="">Characters</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                    </ul>

                    <h2>Shop</h2>
                    <ul>
                        <li><a href="">Shop DC</a></li>
                        <li><a href="">Shop DC Collectibles</a></li>
                    </ul>
                </div>

                <div class="col">
                    <h2>DC</h2>
                    <ul>
                        <li><a href="">Terms Of Use</a></li>
                        <li><a href="">Privacy policy (New)</a></li>
                        <li><a href="">Ad Choices</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscriptions</a></li>
                        <li><a href="">Talent Workshops</a></li>
                        <li><a href="">CPSC Certificates</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>
                    </ul>
                </div>

                <div class="col">
                    <h2>Sites</h2>
                    <ul>
                        <li><a href="">DC</a></li>
                        <li><a href="">MAD Magazine</a></li>
                        <li><a href="">DC Kids</a></li>
                        <li><a href="">DC Universe</a></li>
                        <li><a href="">DC Power Visa</a></li>
                    </ul>
                </div>
                </div>
            </div>
        </div>

        <div class="cta_section">
            <div class="container">
                <a href="" class="btn btn_outline">Sign-up now!</a>

                <nav class="follow_socials">
                    <ul>
                        <li><a href="">Follow Us</a></li>
                        <li>
                            <a href=""><img src="../assets/img/footer-facebook.png" alt=""></a>
                        </li>
                        <li>
                            <a href=""><img src="../assets/img/footer-twitter.png" alt=""></a>
                        </li>
                        <li>
                            <a href=""><img src="../assets/img/footer-youtube.png" alt=""></a>
                        </li>
                        <li>
                            <a href=""><img src="../assets/img/footer-pinterest.png" alt=""></a>
                        </li>
                        <li>
                            <a href=""><img src="../assets/img/footer-periscope.png" alt=""></a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
    </footer>
</template>

<script></script>

<style scoped lang="scss">
    @import '../assets/scss/variables.scss';
    @import '../assets/scss/common.scss';

    #site_footer{
        .footer_links{
            background-image: url('../assets/img/footer-bg.jpg');
            background-repeat: no-repeat;
            background-size: cover;
            .container{
                background: url('../assets/img/dc-logo-bg.png') right center no-repeat;
                background-size: 58%;
            }

            h2{
                color: $fc_light;
                margin: 1rem 0;
                text-transform: uppercase;
            }
            li{
                font-size: $fs_footer_link;
                margin: .5rem 0;
            }
        }

        .cta_section{
            height: $ends_height;
            background: $bg_gray;
            &, .container, ul{
                display: flex;
                align-items: center;
            }
            .container{
                justify-content: space-between;
            }
            .btn{
                color: $fc_light;
            }
            ul li:first-child{
                text-transform: uppercase;
                font-size: 1.2rem;
                font-weight: 800;
                a{
                    color: $dc_primary;
                }
            }
        }
    }
</style>