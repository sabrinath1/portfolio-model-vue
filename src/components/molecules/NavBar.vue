<template>
  <nav class="nav-bar">
    <NavItem text="Serviços" to="/services"></NavItem>
    <NavItem text="Sobre Mim" to="/about"></NavItem>
    <NavItem text="Cases" to="/cases"></NavItem>
    <NavItem text="Contato" to="/contact"></NavItem>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import NavItem from "../atoms/NavItem.vue"
export default defineComponent({ components: { NavItem } })
</script>

<style lang="scss" scoped>
.nav-bar {
  width: max-content;
  display: grid;
  grid-auto-flow: column;
  grid-gap: 2.5rem;
  margin-right: 20px;
}
</style>
