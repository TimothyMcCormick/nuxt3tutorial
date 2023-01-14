<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Nuxt 3 Tutorial</NuxtLink>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
      </nav>
    </header>

    <h2>Home</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime itaque asperiores placeat laudantium veritatis consequatur ad illum exercitationem commodi vitae.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime itaque asperiores placeat laudantium veritatis consequatur ad illum exercitationem commodi vitae.</p>
  </div>
</template>

<script setup>

</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
  p {
    margin: 20px 0;
  }
</style>