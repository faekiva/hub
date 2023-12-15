<script setup lang="ts">
const route = useRoute()
</script>
<!-- https://vuetifyjs.com/en/getting-started/installation/#using-nuxt-3 -->

<template>
  <div>
    <h1>Nuxt Routing set up successfully!</h1>
    <p>Current route: {{ route.path }}</p>
    <a href="https://nuxt.com/docs/getting-started/routing" target="_blank">Learn more about Nuxt Routing</a>
  </div>
</template>
