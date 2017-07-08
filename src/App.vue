<template>
  <div id="app">
    <menu-log-in></menu-log-in>
    <router-view></router-view>
  </div>
</template>

<script>
  import Menu from './components/menu.vue'
export default {
  name: 'app',
  components: {
      'menu-log-in': Menu
  }
}
</script>
