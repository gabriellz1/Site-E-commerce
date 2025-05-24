<script setup>
import Navbar from './components/NavBar.vue'
import HeroBanner from './components/HeroBanner.vue'
import BrandStrip from './components/BrandStrip.vue'
import NewArrivals from './components/NewArrivals.vue'
</script>

<template>
  <div>
    <Navbar />
    <HeroBanner />
    <BrandStrip />
    <NewArrivals />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
