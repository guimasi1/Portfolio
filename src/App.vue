<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import ButtonUpItem from './components/utils/ButtonUpItem.vue'
import FooterItem from '@/components/FooterItem.vue'
</script>

<template>
  <div>
    <nav class="flex justify-center gap-12 pt-1">
      <RouterLink
        to="/"
        class="font-bold text-lg hover:bg-cyan-400 hover:text-white px-4 py-1 rounded-2xl"
        >Home</RouterLink
      >
      <RouterLink
        to="/about"
        class="font-bold text-lg hover:bg-cyan-400 hover:text-white px-4 py-1 rounded-2xl"
        >About</RouterLink
      >
    </nav>
    <div>
      <RouterView />
      <ButtonUpItem />
      <FooterItem />
    </div>
  </div>
</template>

<style></style>
