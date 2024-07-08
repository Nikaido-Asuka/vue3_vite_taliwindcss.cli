<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <div class=" mt-9 ">
    <h1 class=" text-blue-500 text-5xl">{{ msg }}</h1>
  </div>
 
  
</template>

<style scoped>

</style>
