<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores praesentium culpa illo inventore laudantium voluptas suscipit qui repellendus deleniti sit.</p>
  </div>
</template>

<script setup>
  const { id } = useRoute().params
</script>

<style lang="scss" scoped>

</style>