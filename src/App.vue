<template>
  <v-app>
    <v-main class="main pa-0">
      <HomePageVue />
    </v-main>
  </v-app>
</template>

<script setup>
import HomePageVue from "./components/HomePage.vue";
</script>

<style scoped>
.main {
  background-color: #ffffff;
  overflow: hidden;
}
</style>