<template>
  <div class="component">
    <HeaderComponent />
  </div>
  <SocialNetworks></SocialNetworks>
  <ServicesProvided></ServicesProvided>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import HeaderComponent from "./components/organisms/HeaderComponent.vue"
import SocialNetworks from "./components/molecules/SocialNetworks.vue"
import ServicesProvided from "./components/molecules/ServicesProvided.vue"

export default defineComponent({
  components: {
    HeaderComponent,
    SocialNetworks,
    ServicesProvided
  }
})
</script>
