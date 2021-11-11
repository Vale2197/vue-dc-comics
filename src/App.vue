<template>
  <div id="app">
    <site_header/>
    <!-- /header -->

    <site_main/>
    <!-- / site main -->

    <site_footer/>
    <!-- / footer -->

  </div>
</template>

<script>
import site_header from './components/site_header.vue';
import site_main from './components/site_main.vue';
import site_footer from './components/site_footer.vue';

export default {
  name: 'App',
  components: {
      site_header,
      site_main,
      site_footer
  }
}
</script>

<style lang="scss">
  @import "./assets/css_var/colors.scss";

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: monospace;
  }

  #app {
    height: 100vh;
    background-color: cornflowerblue;
  }
</style>
