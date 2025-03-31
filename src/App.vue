<script setup lang=ts>
// It's clearly a TypeScript block, but Biome fails to recognize it.
let num: number = 42;
</script>

<template>
  <h1>Hello, world!</h1>
  <p>num is {{ num }}</p>
</template>

<style scoped>
h1, p {
  font-family: sans-serif;
  color: #e3e3e3;
}
</style>
