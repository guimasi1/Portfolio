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
      <a
        href="#about"
        class="font-bold text-lg hover:bg-cyan-400 hover:text-white px-4 py-1 rounded-2xl"
        >About</a
      >
      <a
        href="#skills"
        class="font-bold text-lg hover:bg-cyan-400 hover:text-white px-4 py-1 rounded-2xl"
        >Skills</a
      >
      <a
        href="#projects"
        class="font-bold text-lg hover:bg-cyan-400 hover:text-white px-4 py-1 rounded-2xl"
        >Projects</a
      >
    </nav>
    <div>
      <RouterView />
      <ButtonUpItem />
      <FooterItem />
    </div>
  </div>
</template>

<style>
html {
  scroll-behavior: smooth;
}
</style>
