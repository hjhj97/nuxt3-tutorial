<template>
  <div>
    <span>{{ counter }}</span>
    <button @click="counter++">+</button>
    <button @click="counter--">-</button>
  </div>
</template>

<script setup>
const counter = useCounter();
</script>

<style lang="scss" scoped></style>
