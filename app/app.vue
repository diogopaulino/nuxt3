<script setup lang="ts">
useSeoMeta({
  title: 'Nuxt 4 Starter',
  description: 'Minimal Nuxt 4 starter updated from the original Nuxt 3 preview experiment.'
})
</script>

<template>
  <main class="page">
    <section>
      <p class="eyebrow">Nuxt 4</p>
      <h1>Minimal starter</h1>
      <p>Small, current and ready to use.</p>
      <a href="https://nuxt.com/docs" target="_blank" rel="noreferrer">Read the docs</a>
    </section>
  </main>
</template>

<style>
:root {
  color-scheme: light dark;
  font-family: Inter, ui-sans-serif, system-ui, sans-serif;
}
body {
  margin: 0;
}
.page {
  min-height: 100vh;
  display: grid;
  place-items: center;
  padding: 2rem;
}
section {
  max-width: 42rem;
}
.eyebrow {
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: .08em;
}
h1 {
  font-size: clamp(2.5rem, 8vw, 5rem);
  margin: .25rem 0 1rem;
}
a {
  display: inline-block;
  margin-top: 1rem;
}
</style>
