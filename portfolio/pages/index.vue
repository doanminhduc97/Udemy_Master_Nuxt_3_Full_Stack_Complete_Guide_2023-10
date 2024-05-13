<template>
  <div>
    Hello from the main page!
  </div>
</template>

<script setup>
useSeoMeta({
  title: 'Main Page',
  description: 'this is the main page',
  ogTitle: 'Main Page',
  ogDescription: '[og:description]',
  ogImage: '[og:image]',
  ogUrl: '[og:url]',
  twitterTitle: 'Main page',
  twitterDescription: '[twitter:description]',
  twitterImage: '[twitter:image]',
  twitterCard: 'summary'
})

useHead({
  htmlAttrs: {
    lang: 'en'
  },
  link: [
    {
      rel: 'icon',
      type: 'image/png',
      href: '/favicon.png'
    }
  ]
})
</script>

<style>
  body {
    @apply bg-white dark:bg-gray-900 text-gray-700 dark:text-gray-300
  }
</style>