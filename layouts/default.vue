<script setup lang="ts">
useHead({
  meta: [
    { property: 'og:title', content: `Fire Photographys` },
    {
      name: 'description',
      content: 'Lets create memories together.',
    },
    {
      property: 'og:description',
      content: 'Lets create memories together.',
    },
    { property: 'og:url', content: 'Lets create memories together.' },
    { name: 'twitter:title', content: 'Lets create memories together.' },
    {
      name: 'twitter:description',
      content: 'Lets create memories together.',
    },
    { name: 'twitter:site', content: 'Lets create memories together.' },
  ],
  title: `Fire Photos`,
})

defineOgImageComponent('Nuxt', {
  headline: 'Greetings 👋',
  title: 'Fire Photos',
  description: 'Capture every moment with Fire Photos.',
})
</script>

<template>
  <main class="min-h-screen overflow-hidden bg-[#faf7f2] dark:bg-background xl:overflow-visible">
    <AppHeader />
    <slot />
    <AppFooter />
  </main>
</template>
