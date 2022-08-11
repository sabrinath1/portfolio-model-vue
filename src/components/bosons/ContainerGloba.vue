<template>
  <div container>
    <slot></slot>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"

export default defineComponent({})
</script>

<style scoped>
.container {
  width: 85%;
  max-width: 1150px;
  margin: 0 auto;
}
</style>
