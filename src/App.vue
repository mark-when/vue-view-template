<script setup lang="ts">
import { useMarkwhenStore } from "./Markwhen/markwhenStore";

const markwhenStore = useMarkwhenStore();
</script>

<template>
  <div>
    {{ markwhenStore.markwhen?.transformed }}
  </div>
</template>

<style scoped></style>
