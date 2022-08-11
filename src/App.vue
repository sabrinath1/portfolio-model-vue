<template>
  <div class="component">
    <HeaderComponent />
    <PresentationMain />
    <ServiceProvided />
    <SocialNetworks></SocialNetworks>
    <ServicesProvided></ServicesProvided>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import HeaderComponent from "./components/organisms/HeaderComponent.vue"
import PresentationMain from "./components/organisms/PresentationMain.vue"
import ServicesProvided from "./components/organisms/ServicesProvided.vue"

export default defineComponent({
  components: {
    HeaderComponent,
    PresentationMain,
    ServicesProvided
  }
})
</script>
<style lang="scss" scoped>
.component {
  width: 85%;
  max-width: 1150px;
  margin: 0 auto;
}
</style>
