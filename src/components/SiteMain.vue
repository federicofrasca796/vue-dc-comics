<template>
    <main id="site_main">
            <section class="content_here">
                <div class="container">
                    <h1>&#8212; Content goes here &#8212;</h1>
                </div>
            </section>

            <div class="buy_info">
                <nav class="container">
                        <ul class="d_flex">
                            <li>
                                <i>
                                    <img src="../assets/img/buy-comics-digital-comics.png" alt="" >
                                </i>
                                <a href="">Digital comics</a>
                            </li>
                            <li>
                                <i>
                                    <img src="../assets/img/buy-comics-merchandise.png" alt="" >
                                </i>
                                <a href="">DC Merchandise</a>
                            </li>
                            <li>
                                <i>
                                    <img src="../assets/img/buy-comics-subscriptions.png" alt="" >
                                </i>
                                <a href="">Subscription</a>
                            </li>
                            <li>
                                <i>
                                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                                </i>
                                <a href="">Comic Shop Locator</a>
                            </li>
                            <li>
                                <i>
                                    <img src="../assets/img/buy-dc-power-visa.svg" alt="" >
                                </i>
                                <a href="">DC Power Visa</a>
                            </li>
                        </ul>
                </nav>
            </div>
    </main>
</template>

<script>
</script>

<style scoped lang="scss">
    @import '../assets/scss/variables.scss';
    @import '../assets/scss/common.scss'; 
    
    .content_here{
        background: $bg_dark;
        color: $fc_light;
        padding: 3rem;
    }
    .buy_info{
        background: $dc_primary;
        ul{
            justify-content: space-around;
            align-items: center;
            padding: 2rem 0;
        }
        li, a{
            color: white;
            text-transform: uppercase;
        }
        li{
            display: flex;
            align-items: center;
            i{
                width: 50px;
            }
            a{
                padding: 1rem;
            }
        }
        img{
            width: 100%;
        }
    }

</style>