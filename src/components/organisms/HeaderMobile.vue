<template>
  <div class="header-mobile">
    <Logo />

    <button class="menu-header-mobile">
      <img class="icon-menu-mobile" src="@/assets/images/hamburguer.png" />
    </button>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import Logo from "../atoms/Logo.vue"

export default defineComponent({
  components: {
    Logo
  }
})
</script>

<style lang="scss" scoped>
@media screen and (max-width: 899px) {
  .header-mobile {
    width: 100%;
    display: grid;
    grid-template-columns: 100px 100px auto;
    align-items: center;
    justify-content: space-evenly;
  }
}
.logo {
  width: 100%;
  height: 50px;
}
.menu-header-mobile {
  border: none;
  background-color: transparent;
  margin-left: 80px;
}
.icon-menu-mobile {
  width: 40px;
  height: 40px;
}
</style>
