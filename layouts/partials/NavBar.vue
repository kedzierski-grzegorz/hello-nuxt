<template>
  <header>
    <nuxt-link to="/" class="logo">Hello Nuxt</nuxt-link>
    <nav>
      <ul>
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="about">About</nuxt-link>
        </li>
        <li>
          <nuxt-link to="services">Services</nuxt-link>
        </li>
        <li>
          <nuxt-link to="contact">Contact</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {}
</script>

<style scoped>
header {
  background: #2299ff;
  display: grid;
  grid-template-columns: repeat(2, auto);
  padding: 0;
}

.logo,
li a {
  padding: 1em 2em;
  display: block;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: bold;
  color: white;
  font-size: 0.9em;
  align-self: center;
}

nav {
  justify-self: right;
}

ul {
  list-style-type: none;
}

li {
  display: inline;
}

li a {
  padding: 1em 2em;
  display: inline-block;
  background: rgba(0, 0, 0, 0.1);
}
</style>
