<script setup lang="ts">
useHead({
  meta: [
    { property: 'og:title', content: `Fire Photographys` },
    {
      name: 'description',
      content: 'Let's create memories together.',
    },
    {
      property: 'og:description',
      content: 'Let's create memories together.',
    },
    { property: 'og:url', content: 'Let's create memories together.' },
    { name: 'twitter:title', content: 'Let's create memories together.' },
    {
      name: 'twitter:description',
      content: 'Let's create memories together.',
    },
    { name: 'twitter:site', content: 'Capture every moment with Fire Photos.' },
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
