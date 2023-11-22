<script setup lang="ts">
import VueMarkdown from 'vue-markdown-render'
import privacyPolicy from '@/assets/privacy.md?raw'
</script>

<template>
  <VueMarkdown :source="privacyPolicy" :options="{html: true, linkify: true, typographer: true}"/>
</template>

<style scoped>

</style>
