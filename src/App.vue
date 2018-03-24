<template>
  <div id="app">
    <toolbar/>
    <div class="wrapper">
      <router-view/>
    </div>
    <footer>

        <div class="container">
          Some Stuff
        </div>

    </footer>
  </div>
</template>

<script>
import toolbar from './components/nav/toolbar';

export default {
  name: 'App',
  components: {
    toolbar: toolbar
  }
};
</script>

<style lang="scss">
  @import "~bulma/bulma";
  $footer: #eee;

  #app {
    box-sizing: border-box;
    background-color: #bbb;
  }
  .wrapper {
    min-height: calc(100vh - 125px);
    border-radius: 0 0 10px 10px;
    background-color: #fff;
    border-bottom: solid 5px #eee;
  }

  footer {
    height: 125px;
    border-radius: 10px 10px 0 0;
    background-color: $footer;
    border-top: 5px solid #ddd;
  }

</style>
