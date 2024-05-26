<script setup lang="ts">
import { RouterView } from 'vue-router'
import TopMenu from './components/TopMenu.vue'
</script>

<template>
  <header>
    <nav>
      <TopMenu />
    </nav>
  </header>

  <body>
    <RouterView />
  </body>
</template>

<style scoped></style>
