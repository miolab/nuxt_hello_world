<template>
  <div class="container">
    <h1>{{ message }}</h1>
    <router-link to="/about">Page About</router-link>
  </div>
</template>

<script>

export default {
  data: function() {
    return {
      message: 'Hello World with Nuxt.js, im!'
    }
  }
}
</script>

<style>
</style>
