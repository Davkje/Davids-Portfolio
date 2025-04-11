<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import HeroSection from './components/HeroSection.vue'
import TechSection from './components/TechSection.vue'
</script>

<template>
  <header>
    <div class="header-wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
  <HeroSection />
  <TechSection />
</template>

<style scoped lang="scss"></style>
