<template>
  <div class="container">
    <h1>{{ message }}</h1>
    <router-link to="/price">Price Page</router-link>
  </div>
</template>

<script>

export default {
  data: function() {
    return {
      message: 'Hello World, IM!'
    }
  }
}
</script>

<style>
</style>
