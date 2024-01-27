<script lang="ts">
import { defineComponent } from 'vue'
import TableRowItem from './TableRowItem/TableRowItem.vue'

export default defineComponent({
  components: { TableRowItem },

  setup() {
    const tableData: TData[] = [
      { sport: 'Running', date: 'today', isDay: true, description: 'it went ok' },
      { sport: 'Cycling', date: 'today', isDay: false, description: 'it went fine' }
    ]

    return {
      tableData
    }
  }
})
</script>

<template>
  <tr v-for="(activity, index) in tableData" :key="index">
    <TableRowItem :activity="activity" />
  </tr>
</template>

<style scoped></style>
