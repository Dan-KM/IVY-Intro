<script setup>
  import { RouterLink, RouterView } from 'vue-router'
  import Navbar from './components/NavBar.vue';
  import FooterComponent from './components/Footer.vue';
</script>

<template>
  <header>
      <nav>
        <Navbar />
      </nav>
  </header>

  <RouterView class = "mt-[5%]"/>

  <FooterComponent />
</template>