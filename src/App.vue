<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
    <p>Hello</p>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>

</style>
