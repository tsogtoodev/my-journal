<template>
  <div class="pb-16">
    <UContainer class="py-4">
      <UHorizontalNavigation :links="links" class="border-b border-gray-200 dark:border-gray-800" />
    </UContainer>

    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Acep Journal',
  ogTitle: 'Acep Journal',
  description: 'This is my personal journal site. So you don\'t belong here.',
  ogDescription: 'This is my personal journal site. So you don\'t belong here.',
  twitterCard: 'summary_large_image',
})

const links = [{
  label: 'Start',
  icon: 'i-heroicons-home',
  to: '/'
}, {
  label: 'Diary',
  icon: 'i-heroicons-book-open',
  to: '/diary'
}, {
  label: 'Thoughts',
  icon: 'i-heroicons-light-bulb',
  to: '/thoughts'
}]
</script>