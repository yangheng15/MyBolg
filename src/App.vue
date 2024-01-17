<template>
  <Header />
  <Sakura />
  <RouterView />
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from '@/components/Header/index.vue'
import Sakura from '@/components/Sakura/index.vue'

</script>

<style scoped></style>
