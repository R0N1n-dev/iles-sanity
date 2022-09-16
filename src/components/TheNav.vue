<template>
  <header class="navbar">
    <section class="navbar-section">
      <router-link to="/" class="btn btn-link text-bold">Home</router-link>
      <router-link to="/about" class="btn btn-link text-bold">About</router-link>
    </section>
    <section class="navbar-section">
      <a href="#" class="btn btn-link">Twitter</a>
      <a href="#" class="btn btn-link">GitHub</a>
    </section>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("../../node_modules/spectre.css/dist/spectre.css");
</style>