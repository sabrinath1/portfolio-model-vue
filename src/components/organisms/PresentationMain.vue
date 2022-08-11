<template>
  <div class="presentation">
    <SocialNetworks></SocialNetworks>
    <img
      class="presentation"
      src="@/assets/images/presentation.svg"
      alt="Apresentação"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import SocialNetworks from "../molecules/SocialNetworks.vue"

export default defineComponent({ components: { SocialNetworks } })
</script>

<style lang="scss" scoped>
.presentation {
  position: relative;
  display: grid;
  justify-content: center;
  .presentation {
    width: 80%;
    justify-self: center;
  }
  .social-networks {
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
  }
  @media screen and (max-width: 899px) {
    .social-networks {
      display: none;
    }
    .presentation {
      width: 100%;
      height: 200px;
    }
  }
}
</style>
