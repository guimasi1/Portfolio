<script setup lang="ts">
import { ArrowUpCircleIcon } from '@heroicons/vue/16/solid'

const scrollToTop = () => {
  window.scroll({
    top: 0,
    left: 0,
    behavior: 'smooth'
  })
}
</script>

<template>
  <div class="sticky bottom-2 left-full me-5 mb-5 w-10 cursor-pointer">
    <ArrowUpCircleIcon @click.prevent="scrollToTop" />
  </div>
</template>
