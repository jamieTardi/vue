<script setup lang="ts">
import styles from './TableHeader.module.scss'
import TableHeader from './TableHeader/TableHeader.vue'
import TableRows from './TableRows/TableRows.vue'
</script>

<template>
  <table :class="styles.header">
    <TableHeader />
    <TableRows />
  </table>
</template>

<style lang="scss" scoped></style>
