<script setup lang="ts">
import VueMarkdown from 'vue-markdown-render'
import tos from '@/assets/tos.md?raw'
</script>

<template>
  <VueMarkdown :source="tos" :options="{html: true, linkify: true, typographer: true}"/>
</template>

<style scoped>

</style>
