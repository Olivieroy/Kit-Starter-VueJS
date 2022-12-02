<script setup>
import { RouterLink, RouterView } from "vue-router";
import Header from "./layouts/Header.vue";
import Footer from "./layouts/Footer.vue";

</script>

<template>

  <Header/>

  <main class="main">
      
    <RouterView />

  </main>
  <Footer/>
</template>

<style lang="scss">

@use 'sass/global' as *;

.main{
    max-width: rem(1200);
    margin: auto;
    padding: rem(0) rem(16);
    min-height: 100vh;
}
</style>

