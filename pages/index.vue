<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script lang="ts" setup>
definePageMeta({
  middleware: 'auth',
})
</script>