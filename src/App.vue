<template>
  <div class="component">
    <Logo />
    <NavBar />
    <SearchForm></SearchForm>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import { Logo } from "@/components/atoms"
import NavBar from "@/components/molecules/NavBar.vue"
import SearchForm from "@/components/molecules/SearchForm.vue"

export default defineComponent({
  components: {
    NavBar,
    Logo,
    SearchForm
  }
})
</script>

<style lang="scss" scoped>
.component {
  width: 300px;
}
</style>
