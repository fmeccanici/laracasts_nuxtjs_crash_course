<script setup lang="ts">
  const title = useState('title');
</script>

<template>
  <div class="container mx-auto w-1/2 py-8">
    <Title>{{ $route.params.id }} | {{ title }}</Title>
    <h3 class="text-3xl font-bold"><NuxtLink to="/posts/1"/>Title of Post</h3>
    <div class="post-meta text-gray-700 flex items-center space-x-2">
      <div>Feb 2, 2022</div>
      <div>&middot;</div>
      <div>Floris Meccanici</div>
    </div>
    <div class="post-content mt-4">
      {{ $route.params.id }} Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deleniti dolor et fugit laborum nemo repellat repudiandae? Amet eveniet itaque labore necessitatibus officiis optio quis repellat rerum, sequi sint sit ullam veritatis voluptate, voluptatibus voluptatum. Ab aut culpa deleniti dolore eligendi nemo nisi praesentium recusandae, reprehenderit unde velit veniam vitae? Dolore facere labore nam praesentium quibusdam! Dolores doloribus earum excepturi laborum, quas tempora veritatis? Asperiores cum error nobis provident tenetur? Ab amet aperiam aspernatur assumenda distinctio doloribus ducimus earum enim eveniet exercitationem id illo inventore iusto laborum libero, minima neque nostrum odio omnis quasi quis quos repudiandae sequi tempore ullam voluptates!
    </div>
  </div>
</template>

<style scoped>

</style>