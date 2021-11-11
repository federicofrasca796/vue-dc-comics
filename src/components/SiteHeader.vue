<template>
    <header id="site_header" class="d_flex">
      <div class="container">
        <img src="../assets/img/dc-logo.png" alt="DC logo" width="70px">

        <nav>
          <ul>
            <li><a href="">Characters</a></li>
            <li class="active"><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Collectibles</a></li>
            <li><a href="">Videos</a></li>
            <li><a href="">Fans</a></li>
            <li><a href="">News</a></li>
            <li><a href="">Shop</a></li>
          </ul>
        </nav>
      </div>
    </header>
</template>

<script>

</script>

<style scoped lang="scss">
  @import '../assets/scss/variables.scss';
  @import '../assets/scss/common.scss';  

  #site_header{
    height: $ends_height;
    background: #ffff;
    align-items: center;
    .container{
        justify-content: space-between;
        /* align-items: center;
        height: 100%; */
    }
    /* nav{
      height: 100%;
      align-items: center;
    } */
    .container, nav, ul, li {
      display:flex;
      height: 100%;
      align-items: center;
    }
    li{
      a{
        color: $fc_gray90;
      }
      text-transform: uppercase;
      font-size: $fs_header;
      font-weight: 800;

      &.active, &:hover{
        /* border-bottom: 3px solid $dc_primary;
        padding-bottom: -3px; */
        box-shadow: 0 -3px 0 $dc_primary inset;
      }
    }

  }
</style>