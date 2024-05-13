<template>
  <div>
    <div>This is another layout</div>
    <slot></slot>
  </div>
</template>

<script setup>
useSeoMeta({
  title: 'Another Page',
  description: 'this is the main page',
  ogTitle: 'Main Page',
  ogDescription: 'this is the description',
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