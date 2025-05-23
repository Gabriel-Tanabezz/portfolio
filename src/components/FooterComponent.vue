<template>
  <footer class="bg-gray-800 text-white text-center p-4 mt-10">
    © {{ currentYear }} Gabriel Tanabe Kavaguchi
  </footer>
</template>

<script setup>
const currentYear = new Date().getFullYear()
</script>
