<script setup lang="ts">

</script>

<template>
  <div class="post-container py-8">
    <h3 class="text-3xl font-bold"><NuxtLink to="/posts/1"/>Title of Post</h3>
    <div class="post-meta text-gray-700 flex items-center space-x-2">
      <div>Feb 2, 2022</div>
      <div>&middot;</div>
      <div>Floris Meccanici</div>
    </div>
    <div class="post-preview leading-relaxed mt-4">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci aut, consectetur delectus dolore itaque iusto magni minima non nostrum porro quis recusandae reiciendis similique sunt voluptatum? Aperiam culpa error illum, itaque iusto natus neque non, quidem quis quo quod suscipit? Aliquid debitis dolorem doloremque eveniet labore maxime ratione rem, totam?
    </div>
    <div class="mt-4">
      <NuxtLink to="/posts/1" class="bg-blue-700 hover:bg-blue-800 text-white rounded inline-block px-4 py-2">Read more</NuxtLink>
    </div>
  </div>
</template>

<style scoped>

</style>