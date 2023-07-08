<template>
  <header class="header">
    <nuxt-link to="/"> <h1 class="title">Dad Jokes</h1></nuxt-link>
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>

      <li>
        <nuxt-link to="/jokes">Jokes</nuxt-link>
      </li>

      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>

      <li>
        <a href="http://www.github.com/sideshow-charles" class="github">Github</a>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.1rem;
  padding-bottom: 0.2rem;
  border-bottom: 1px solid #ccc;
}

.header .title {
  font-size: 1.8rem;
  color: #526488;
}

.header ul {
  display: flex;
}

.header a {
  display: inline-block;
  /*background: #526488;*/
  color: #526488;
  padding: 0.5rem 1rem;
  text-decoration: none;
  font-size: 1.1rem;
  margin-right: 0.2rem;
}

.github {
  background-color: #526488;
  color: white !important;
}
</style>
