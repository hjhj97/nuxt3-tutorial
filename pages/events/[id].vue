<template>
  <div>Event id : {{ $route.params.id }}</div>
</template>

<script setup>
const route = useRoute();
const nuxt = useNuxtApp();
console.log(nuxt);
</script>

<style scoped></style>
