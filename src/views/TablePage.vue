<script setup lang="ts">
import TableContainer from '../components/TableComponents/TableContainer.vue'
</script>

<template>
  <div class="about">
    <h1>Table</h1>
    <TableContainer />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
