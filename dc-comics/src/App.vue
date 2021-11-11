<template>
  <div id="app">
    <header id="site_header">
      <div class="logo">
        <img src="./assets/img/dc-logo.png" alt="">
      </div>
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
    </header>
    <!-- /#site_header -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
  }
}
</script>

<style lang="scss">
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

#site_header{
  height: 100px;
  
}

</style>
