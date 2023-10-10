<template>
  <div>This is Home</div>
</template>

<script setup>
//const { sayHello } = useUtils();
//const { $hello } = useNuxtApp();
//$hello("!!");
//sayHello();
definePageMeta({
  middleware: "hello",
});
</script>

<style scoped></style>
