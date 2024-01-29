<script setup lang="ts">
defineProps<{ activity: TData }>()
</script>

<template>
  <td>{{ activity.sport }}</td>
  <td>{{ activity.date }}</td>
  <td>{{ activity.isDay ? 'Daytime' : 'NIghtime' }}</td>
  <td>{{ activity.sport }}</td>
</template>

<style lang="scss" scoped></style>
