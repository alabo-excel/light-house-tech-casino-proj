<script setup>
import Home from "./views/Home.vue";
import HeaderNav from "./components/HeaderNav.vue";
import FooterNav from "./components/FooterNav.vue";
</script>

<template>
  <div class="app">
    <HeaderNav />
    <Home />
    <FooterNav />
  </div>
</template>

<style scoped>
.app{
  background-image: url("./assets/background.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
