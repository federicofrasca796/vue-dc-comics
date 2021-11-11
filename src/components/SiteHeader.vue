<template>
    <header id="site_header" >
      <div class="container d_flex">
        <img src="../assets/img/dc-logo.png" alt="DC logo" width="70px">

        <nav>
          <ul>
            <li>Characters</li>
            <li class="active">Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Collectibles</li>
            <li>Videos</li>
            <li>Fans</li>
            <li>News</li>
            <li>Shop</li>
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
    display: flex;
    align-items: center;
    .container{
        justify-content: space-between;
        align-items: center;
    }

    li{
        display: inline-block;
        margin: .5rem;
        height: 100%;
        color: $fc_gray90;
        text-transform: uppercase;
        font-size: $fs_header;
        font-weight: 800;

        &.active{
          border-bottom: 3px solid $dc_primary;
        }
    }

  }
</style>