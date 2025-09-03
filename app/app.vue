<script setup lang="ts">
// import AppHeader from "~~/components/AppHeader.vue";

const hell = ref('Hell')
</script>
<template>
  <div>
    {{ hell }}
    <AppHeader />
    <MyTest />
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>