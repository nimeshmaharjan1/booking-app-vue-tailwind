<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import Header from "./components/Header.vue";
import LoginView from "./views/LoginView.vue";
</script>

<template>
  <main>
    <LoginView />
    <Header />
    <RouterView />
  </main>
</template>

<style>
@import "@/assets/base.scss";
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@100;300;400;600;700&display=swap");
* {
  font-family: "Montserrat", sans-serif;
}
</style>
