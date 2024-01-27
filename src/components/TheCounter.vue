<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)

const updateCount = (passedCount: number) => {
  if (passedCount > count.value) {
    count.value++
    return
  }
  count.value--
}
</script>

<template>
  <button @click="updateCount(count + 1)">Increase</button>
  <div>{{ count }}</div>
  <button @click="updateCount(count - 1)">Decrease</button>
</template>

<style scoped />
