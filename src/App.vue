<script setup>
import { ref, onMounted } from "vue";
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import HomeCards from "./components/HomeCards.vue";
</script>

<template>
  <Navbar></Navbar>
  <Hero></Hero>
  <HomeCards></HomeCards>
</template>
