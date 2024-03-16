<script setup>
import {ref} from 'vue'
const a=ref('new Page!')
</script>

<template>
  <div class="text-3xl font-bold underline">{{ a }}</div>
  <span class="border-sky-200 border-[1px] w-40 h-20 text-center block">测试[]</span>
</template>

<style scoped>

</style>
