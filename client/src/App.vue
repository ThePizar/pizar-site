<template>
  <div id="app">
    <nav class="navbar">
      <div class="container nav-background">
        <router-link to="/" class="navbar-item">Home</router-link>
        <a class="navbar-item" href="https://github.com/ThePizar/pizar-site/">Github</a>
        <router-link to="/poems" class="navbar-item">Poetry</router-link>
      </div>
    </nav>
    <router-view></router-view>
  </div>
</template>

<script>
  export default {
    name: 'app',
    data () {
      return {
        msg: 'Welcome to Pizar\'s Site'
      }
    }
  }
</script>

<style scoped>
  .nav-background {
    background: #47d1b1
  }
</style>