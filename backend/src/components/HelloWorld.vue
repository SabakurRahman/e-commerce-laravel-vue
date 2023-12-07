<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
    <h1 class="bg-amber-800">{{ msg }}</h1>
    <h2  >Essential Links</h2>

</template>

<style scoped>

</style>
