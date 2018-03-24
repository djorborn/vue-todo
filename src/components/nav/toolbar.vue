<template lang="pug">
  #toolbar.navbar.is-primary
    .navbar-brand
      a(href="/").navbar-item.is-large todo
      .navbar-burger.burger#burger(v-on:click="toggleMenu")
        span
        span
        span
    navbar-menu#menu
</template>

<script>
import navbarMenu from './navbarMenu';
var burger = document.getElementById('burger');
var menu = document.getElementById('menu');

export default {
  name: 'toolbar',
  components: {
    'navbar-menu': navbarMenu
  },
  methods: {
    toggleMenu: function () {
      burger.classList.add('is-active');
      menu.classList.toggle('is-active');
    }
  }
}
</script>

<style lang="css">
</style>
