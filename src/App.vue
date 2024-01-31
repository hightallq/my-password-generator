<script setup lang="ts">
import PasswordGenerator from "./components/PasswordGenerator.vue";
import { NMessageProvider } from "naive-ui"
</script>

<template>
  <NMessageProvider>
    <PasswordGenerator />
  </NMessageProvider>
</template>

<style scoped>
body {
  background-color: darkblue;
}
</style>
