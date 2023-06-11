<script setup lang="ts">
  const route = useRoute()
</script>

<template>
  <NuxtLayout>
    <NuxtPage :page-key="route.fullPath" />
  </NuxtLayout>
</template>

<style scoped lang="scss">
  $w: 1px;
</style>
