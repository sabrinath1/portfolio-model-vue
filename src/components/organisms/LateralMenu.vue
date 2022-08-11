<template>
  <div class="lateral-menu">
    <NavBar />
    <SocialNetworks />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import NavBar from "../molecules/NavBar.vue"
import SocialNetworks from "../molecules/SocialNetworks.vue"

export default defineComponent({
  components: {
    NavBar,
    SocialNetworks
  }
})
</script>

<style lang="scss" scoped>
.menu-lateral {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #00856f;
  width: 80vw;
  height: 100vh;
  position: absolute;
  left: -100vw;
  transition: 0.25s;
  position: fixed;
  padding-top: 20px;
}
</style>
