<script setup>
import Navbar from './components/NavBarComponent.vue'
import Footer from './components/FooterComponent.vue'
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <Navbar />
    <main class="flex-grow container mx-auto px-4 py-6">
      <router-view />
    </main>
    <Footer />
  </div>
</template>
