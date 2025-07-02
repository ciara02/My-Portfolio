<template>
<div class="bg-[#111827] min-h-screen">
  <NavBar/>
  <HeroSection/>
  <ServicesSection/>
  <AboutSection/>
  <ExperienceAndSkills/>
  <LatestProjectSection/>
  <ContactSection/>
</div>
</template>

<script setup>
import { defineAsyncComponent } from "vue";
// import HeroSection from '@/components/HeroSection.vue'
const NavBar = defineAsyncComponent(() => import('@/components/NavBar.vue'));
const HeroSection = defineAsyncComponent(() => import('@/components/HeroSection.vue')); 
const ServicesSection = defineAsyncComponent(() => import('@/components/ServicesSection.vue'));  
const AboutSection = defineAsyncComponent(() => import('@/components/AboutSection.vue'));  
const ContactSection = defineAsyncComponent(() => import('@/components/ContactSection.vue'));  
const ExperienceAndSkills = defineAsyncComponent(() => import('@/components/ExperienceAndSkills.vue'));  
const LatestProjectSection = defineAsyncComponent(() => import('@/components/LatestProjectSection.vue'));  
</script>