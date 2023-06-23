<template>
  <div>
    <ul class="mainMenu">
      <li><NuxtLink to="/">INDEX</NuxtLink></li>
      <li><NuxtLink to="/contractors">/contractors</NuxtLink></li>
      <li><NuxtLink to="/contractors/123123123">/contractors/clientId</NuxtLink></li>
      <li><NuxtLink to="/contractors/123123123/2234">/contractors/clientId/officeId</NuxtLink></li>
    </ul>
  </div>
  <NuxtPage />
</template>

<script setup lang="ts">
</script>

<style scoped>
.mainMenu {
  background-color: #d3d3d3;
}
</style>
