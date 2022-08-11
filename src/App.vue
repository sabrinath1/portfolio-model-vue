<template>
  <div class="header-mobile">
    <HeaderMobile />
  </div>
  <div class="component">
    <div class="header-desktop">
      <HeaderComponent />
    </div>

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
import HeaderMobile from "./components/organisms/HeaderMobile.vue"

export default defineComponent({
  components: {
    HeaderComponent,
    PresentationMain,
    ServicesProvided,
    HeaderMobile
  }
})
</script>
<style lang="scss" scoped>
.component {
  width: 85%;
  max-width: 1150px;
  margin: 10px auto;
}
@media screen and (min-width: 900px) {
  .header-mobile {
    display: none;
  }
}
@media screen and (max-width: 899px) {
  .header-desktop {
    display: none;
  }
}
</style>
