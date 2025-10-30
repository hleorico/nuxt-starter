<script setup>
useHead({
  htmlAttrs: { lang: 'en' },
  title: 'Leo H — CX & Operations Strategist',
  meta: [
    { name: 'description', content: 'I help founders run smoother. CX and operations systems that bring clarity, speed, and calm.' },

    // Open Graph / social
    { property: 'og:title', content: 'Leo H — CX & Operations Strategist' },
    { property: 'og:description', content: 'Calm systems for busy founders. Notion, ClickUp, automation, SOPs.' },
    { property: 'og:type', content: 'website' },
    { property: 'og:url', content: 'https://YOUR-SITE.netlify.app' },
    { property: 'og:image', content: '/og.jpg' },

    // Twitter
    { name: 'twitter:card', content: 'summary_large_image' },
    { name: 'twitter:title', content: 'Leo H — CX & Operations Strategist' },
    { name: 'twitter:description', content: 'Calm systems for busy founders.' },
    { name: 'twitter:image', content: '/og.jpg' }
  ],
  bodyAttrs: { class: 'font-sans' }
});
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
