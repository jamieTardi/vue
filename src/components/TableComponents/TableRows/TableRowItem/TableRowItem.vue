<script lang="ts">
import { PropType } from 'vue'

type TProps = {
  activity: TData
}
export default {
  props: {
    activity: {
      type: Object as PropType<TProps>,
      required: true
    }
  },
  data(props) {
    console.log(props.sport)
  }
}
</script>

<template>
  <td>{{}}</td>
</template>

<style lang="scss" scoped></style>
