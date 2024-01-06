<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="flex items-center justify-center rounded-lg border border-gray-100 bg-gray-100 p-1">
    <RouterLink
      to="/"
      class="block rounded-md px-4 py-2 text-sm text-gray-500 hover:text-gray-700 focus:relative"
      >Dashboard</RouterLink
    >
    <RouterLink
      to="/menu-item"
      class="block rounded-md px-4 py-2 text-sm text-gray-500 hover:text-gray-700 focus:relative"
      >Menu Item</RouterLink
    >
  </header>
  <RouterView />
</template>
