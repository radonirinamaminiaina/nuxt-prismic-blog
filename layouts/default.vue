<template>
  <header class="bg-yellow-500 mb-6">
    <nav class="container-section flex gap-4 h-14 items-center">
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/blog">Blog</NuxtLink>
    </nav>
  </header>
  <main class="container-section">
    <slot></slot>
  </main>
</template>
