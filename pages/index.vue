<template>
  <div>
    This is Home
    <span>{{ counter }}</span>
    <Counter />
  </div>
</template>

<script setup>
import { useCounterStore } from "~/stores/myStore";
//const { sayHello } = useUtils();
//const { $hello } = useNuxtApp();
//$hello("!!");
//sayHello();
//definePageMeta({
//  middleware: "hello",
//});
//const counterStore = useCounterStore();
//const counter = useCounter();

const res = await $fetch("/api/hello");
console.log(res);
</script>

<style scoped></style>
