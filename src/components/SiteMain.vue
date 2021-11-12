<template>
    <main id="site_main">
        <div class="jumbo">

        </div>

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
                                <img src="../assets/img/buy-comics-digital-comics.png" alt="" width="80%" >
                            </i>
                            <a href="">Digital comics</a>
                        </li>
                        <li>
                            <i>
                                <img src="../assets/img/buy-comics-merchandise.png" alt="" width="80%" >
                            </i>
                            <a href="">DC Merchandise</a>
                        </li>
                        <li>
                            <i>
                                <img src="../assets/img/buy-comics-subscriptions.png" alt="" width="90%" >
                            </i>
                            <a href="">Subscription</a>
                        </li>
                        <li>
                            <i>
                                <img src="../assets/img/buy-comics-shop-locator.png" alt="" width="65%">
                            </i>
                            <a href="">Comic Shop Locator</a>
                        </li>
                        <li>
                            <i>
                                <img src="../assets/img/buy-dc-power-visa.svg" alt="" width="100%" >
                            </i>
                            <a href="">DC Power Visa</a>
                        </li>
                    </ul>
            </nav>
        </div>
    </main>
</template>

<script>
export default {
    // props: ,
    data(){
        return {
            games: [
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
    },
}

</script>

<style scoped lang="scss">
    @import '../assets/scss/variables.scss';
    @import '../assets/scss/common.scss'; 
    
    #site_main{
        .jumbo{
            height: 350px;
            background-image: url('../assets/img/jumbotron.jpg');
            background-size: cover;
            background-position: top center;
        }
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
                width: 60px;
                text-align: center;
            }
            a{
                padding: 1rem;
            }
        }
        /* img{
            width: 100%;
        } */
        }
    }

</style>