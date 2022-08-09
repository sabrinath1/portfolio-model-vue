<template>
  <div class="component">
    <HeaderComponent />
    <PresentationMain />
  </div>
  <SocialNetworks></SocialNetworks>
  <ServicesProvided></ServicesProvided>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import HeaderComponent from "./components/organisms/HeaderComponent.vue"
import PresentationMain from "./components/organisms/PresentationMain.vue"
export default defineComponent({
  components: {
    HeaderComponent,
    PresentationMain
  }
})
</script>
