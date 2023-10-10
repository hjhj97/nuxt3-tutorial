<template>
  <div>This is Home</div>
</template>

<script setup>
const { sayHello } = useUtils();
const { $hello } = useNuxtApp();
$hello("!!");
sayHello();
</script>

<style scoped></style>
