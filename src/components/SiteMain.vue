<template>
    <main id="site_main">
            <section class="content_here">
                <div class="container">
                    <h1>&#8212; Content goes here &#8212;</h1>
                </div>
            </section>

            <div class="buy_info">
                <div class="container d_flex">
                    <nav>
                        <ul>
                            <li>
                                <a href="">Digital comics</a>
                            </li>
                            <li>
                                <a href="">DC Merchandise</a>
                            </li>
                            <li>
                                <a href="">Subscription</a>
                            </li>
                            <li>
                                <a href="">Comic Shop Locator</a>
                            </li>
                            <li>
                                <a href="">DC Power Visa</a>
                            </li>
                        </ul>
                    </nav>
                </div>
            </div>
    </main>
</template>

<script>
</script>

<style scoped lang="scss">
    @import '../assets/scss/variables.scss';
    @import '../assets/scss/common.scss'; 
    
    #site_main{
    }
    .content_here{
        background: $bg_dark;
        color: $fc_light;
        padding: 3rem;
    }
    .buy_info{
        justify-content: space-around;
        background: $dc_primary;
    }

</style>