<template>
  <div>
    <Title>Nuxt 3 example</Title>
    <nav>
      <ul>
        <li><NuxtLink href="/">Home</NuxtLink></li>
        <li><NuxtLink href="/about">About</NuxtLink></li>
        <li><NuxtLink href="/contact">Content</NuxtLink></li>
      </ul>
    </nav>
    <slot/>
  </div>
</template>