<script setup>
    import footerLogo from '@/assets/images/footer-logo.png'
</script>

<template>
  <footer>
    <img :src="footerLogo" alt="Footer logo">
    Boxify &copy; 2025
  </footer>
</template>

<style scoped>
  footer {
    display:flex;
    flex-direction:column;
    align-items:center;
    gap:5px;
  }
</style>