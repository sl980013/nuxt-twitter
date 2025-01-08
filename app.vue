<template>
  <div class="{'dark': darkMode}">
    <NuxtRouteAnnouncer />
    <h1 class="text-red-500 dark:text-dim-600">Twitter clone</h1>
  </div>
</template>
<script setup>
const darkMode = ref(true)
</script>
