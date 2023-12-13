<template>
  <div>
    <Html :lang="dynamic > 50 ? 'en_GB' : 'en-US'">
    <Head>
      <Title>Top 50 Restaurants</Title>
      <Meta
          name="description"
          content="Restaurantly"
      />
      <Link rel="preload" href="https://nuxtjs.ir/logos/nuxt-white.svg" as="script"></Link>
    </Head>
    </Html>
    <NuxtLayout name="custom">
      <div class="container">
        <RestaurantTable />
      </div>
    </NuxtLayout>
  </div>
</template>
<script setup lang="ts">
</script>