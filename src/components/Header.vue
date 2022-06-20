<template>
  <header class="bg-cyan-700 text-white py-2 rounded-b-md mb-4">
    <nav class="container flex flex-row py-4 pb-5 items-center justify-between">
      <div class="brand-title">
        <h1 class="text-3xl font-semibold">Namastay</h1>
      </div>
      <div class="nav-links flex flex-row gap-5">
        <RouterLink
          class="text-xl font-medium border-solid border-b border-cyan-700 hover:border-cyan-200 transition-all duration-300 hover:shadow-cyan-200/80"
          to="/"
          >Home</RouterLink
        >
        <RouterLink
          class="text-xl font-medium border-b border-solid border-cyan-700 hover:border-cyan-200 transition-all duration-300"
          to="/about"
          >About</RouterLink
        >
        <RouterLink
          class="text-xl font-medium border-solid border-b border-cyan-700 hover:border-cyan-200 transition-all duration-300 hover:shadow-cyan-200/80"
          to="/hotels"
          >Hotels</RouterLink
        >
        <RouterLink
          class="text-xl font-medium border-solid border-b border-cyan-700 hover:border-cyan-200 transition-all duration-300 hover:shadow-cyan-200/80"
          to="/hotels"
          >Contact Us</RouterLink
        >
      </div>
    </nav>
  </header>
</template>
<script lang="ts" script>
import { RouterLink } from "vue-router";
</script>
<style lang="scss" scoped>
a {
  padding: 0.5rem 1rem;
}
</style>
