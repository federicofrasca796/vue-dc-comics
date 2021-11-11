<template>
  <div id="app">
    <SiteHeader/>
    <!-- /#site_header -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import SiteHeader from './components/SiteHeader.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
  }
}
</script>

<style lang="scss">
@import './assets/scss/variables.scss';
@import './assets/scss/common.scss';

</style>
