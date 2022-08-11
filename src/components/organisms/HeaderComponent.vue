<template>
  <header class="header">
    <Logo />
    <NavBar />
    <SearchForm></SearchForm>
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import Logo from "@/components/atoms/Logo.vue"
import NavBar from "@/components/molecules/NavBar.vue"
import SearchForm from "@/components/molecules/SearchForm.vue"

export default defineComponent({
  components: { NavBar, Logo, SearchForm }
})
</script>
<style lang="scss" scoped>
.header {
  width: 100%;
  display: grid;
  grid-template-columns: 160px repeat(2, auto);
  align-items: center;
  justify-content: space-around;
}
</style>
