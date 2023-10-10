<template>
  <div class="Custom">
    Custom
    <img src="/sample.jpg" alt="" />
    <IconsBell />
  </div>
</template>

<script setup>
const { sayHello } = useUtils();
sayHello();
definePageMeta({
  layout: "custom",
});
</script>

<style lang="scss" scoped></style>
