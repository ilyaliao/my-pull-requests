<script setup>
useHead({
  htmlAttrs: {
    lang: 'en',
  },
})
</script>

<template>
  <UApp>
    <NuxtPage />
    <div class="flex flex-wrap justify-center items-center gap-2 p-4">
      <span class="text-sm text-gray-600 dark:text-gray-400">Deployed at</span>
      <UButton
        to="https://zeabur.com"
        target="_blank"
        variant="ghost"
        size="xs"
        color="violet"
        icon="i-material-icon-theme:zeabur-light"
      >
        Zeabur
      </UButton>
    </div>
    <ScrollToTop />
  </UApp>
</template>

<style lang="postcss">
body {
  @apply min-h-screen bg-white dark:bg-neutral-900 text-neutral-700 dark:text-neutral-200 font-sans;
}
</style>
