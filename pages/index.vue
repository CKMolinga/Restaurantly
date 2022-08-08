<template>
  <div>
    <Html :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
      <Head>
        <Title>Restaurantly</Title>
        <Meta
          name="description"
          content="Restaurantly is a restaurant search engine"
        />
        <Link
          rel="preload"
          href="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691.png"
          as="script"
        ></Link>
      </Head>
    </Html>
    <div class="container">
      <h1>Welcome To Restaurantly</h1>
      <NuxtLink to="/restaurants">Explore Restaurants</NuxtLink>
    </div>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}
</style>
