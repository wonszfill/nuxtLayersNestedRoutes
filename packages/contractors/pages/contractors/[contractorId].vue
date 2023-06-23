<template>
  <div>
    <h2>/contractorId Nested pages</h2>
    <ul>
      <li><NuxtLink :to="`/contractors/${contractorId}/client-terms`">/client-terms</NuxtLink></li>
      <li><NuxtLink :to="`/contractors/${contractorId}/client-profile`">/client-profile</NuxtLink></li>
    </ul>
    <NuxtPage />
  </div>
</template>
<script setup lang="ts">
import { computed } from 'vue'
const route = useRoute()

const contractorId = computed(() => route.params?.contractorId)
</script>