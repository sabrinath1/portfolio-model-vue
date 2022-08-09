<template>
  <div class="component">
    <Logo />
    <NavBar />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import { Logo } from "@/components/atoms"
import NavBar from "@/components/molecules/NavBar.vue"

export default defineComponent({
  components: {
    NavBar,
    Logo
  }
})
</script>

<style lang="scss" scoped>
.component {
  width: 300px;
}
</style>
