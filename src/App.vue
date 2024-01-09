<script setup>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

import Main from "./components/Main.vue";
</script>

<template>
  <div class="wrapper">
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<style lang="sass" scoped>
.wrapper
  display: flex
  flex-direction: column
  height: 100vh
</style>
