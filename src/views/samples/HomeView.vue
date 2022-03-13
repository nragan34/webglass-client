<script setup>
import TheWelcome from "@/components/TheWelcome.vue";
import { ref } from 'vue'
const count = ref(0)
</script>

<template>
  <main>
    <TheWelcome />
    The Count: {{count}}
  </main>
</template>
