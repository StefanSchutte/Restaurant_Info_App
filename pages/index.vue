<template>
  <div>
<Html :lang="dynamic > 50 ? 'en_GB' : 'en-US'">
<Head>
  <Title>Restaurantly</Title>
  <Meta
      name="description"
      content="Restaurantly"
  />
  <Link rel="preload" href="https://nuxtjs.ir/logos/nuxt-white.svg" as="script"></Link>
</Head>
</Html>
    <div class="container">
      <h1>Welcome to Restaurantly</h1>
      <a href="/restaurants">Go to Restaurants </a>
    </div>

  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;

}
</style>
<script setup lang="ts">
</script>