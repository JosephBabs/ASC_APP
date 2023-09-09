<script setup lang="ts">
useHead({
  title: 'Africa sound City',
  meta: [
    { name: 'description', content: 'Africa Sound City website.' },
  ],
  link: [
    { rel: 'icon', type: 'image/png', href: '/logo.png' }
  ],
})
</script>
<template>
    <div>
        <SectionsHomeHeroSection/>
        <SectionsHomeLatestPodcast/>
        <SectionsHomePopularPodcasts/>
        <SectionsAboutPodux/>
        <SectionsWhyUs/>
        <SectionsCallToAction/>
    </div>
</template>