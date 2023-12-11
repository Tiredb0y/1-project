<script setup>
import footervue from '@/components/footervue.vue'
import headervue from '@/components/headervue.vue'
import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
  <headervue></headervue>
  <RouterView></RouterView>
<footervue></footervue>
</template>
<style scoped>

</style>