<template>
  <div class="container">
    <h1>About page</h1>
    <h2>Title about</h2>
    <p>
      Consequatur eos veritatis asperiores placeat veritatis aspernatur. At
      omnis rerum quo aperiam voluptatem. Itaque temporibus in doloribus dolor.
    </p>
  </div>
</template>

<script>
export default {
  transition: 'bounce',
  head() {
    return {
      title: 'About page',
      meta: [{ name: 'description', content: 'My description' }]
    }
  }
}
</script>

<style></style>
