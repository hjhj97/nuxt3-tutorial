<template>
  <div>
    This is Home
    <div>{{ pending ? "pending..." : product }}</div>

    <!--<Counter />-->
  </div>
</template>

<script setup>
import { useCounterStore } from "~/stores/myStore";
//const { sayHello } = useUtils();
//const { $hello } = useNuxtApp();
//$hello("!!");
//sayHello();
//definePageMeta({
//  middleware: "hello",v
//});
//const counterStore = useCounterStore();
//const counter = useCounter();

const { data: product, pending } = await useLazyFetch("/api/product", {
  transform: (_product) => _product.data,
});
console.log(product);
</script>

<style scoped></style>
