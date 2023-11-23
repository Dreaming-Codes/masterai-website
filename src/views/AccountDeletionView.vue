<script setup lang="ts">
import VueMarkdown from 'vue-markdown-render'
import accountDeletion from '@/assets/account-deletion.md?raw'
</script>

<template>
  <VueMarkdown :source="accountDeletion" :options="{html: true, linkify: true, typographer: true}"/>
</template>

<style scoped>

</style>
