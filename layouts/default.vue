<template>
  <div>
    <NavBar />
    <nuxt />
  </div>
</template>
<script>
import NavBar from './partials/NavBar'

export default {
  components: {
    NavBar
  }
}
</script>
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
}
</style>
