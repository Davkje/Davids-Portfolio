<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HeroSection from '../components/HeroSection.vue'
import TechSection from '../components/TechSection.vue'
import FeaturedProjects from '../components/FeaturedProjects.vue'
import SkillsSection from '../components/SkillsSection.vue'
import ContactSection from '../components/ContactSection.vue'
</script>

<template>
  <main class="home">
    <HeroSection />
    <TechSection />
    <FeaturedProjects />
    <SkillsSection />
    <ContactSection />
  </main>
</template>

<style scoped lang="scss">
h1 {
  color: #42b983;
}
</style>
