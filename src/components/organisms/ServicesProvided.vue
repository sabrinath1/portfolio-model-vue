<template>
  <div class="services">
    <ServiceProvided
      title="Front End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, voluptas. Nam cupiditate non fugiat unde inventore, nobis illo distinctio id voluptatum amet ullam officia rem aspernatur provident facilis nulla dolores!"
    />
    <ServiceProvided
      title="Back End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, voluptas. Nam cupiditate non fugiat unde inventore, nobis illo distinctio id voluptatum amet ullam officia rem aspernatur provident facilis nulla dolores!"
    />
    <ServiceProvided
      title="Manutenção"
      description="Lorem ipsum dolor sit amet
    consectetur adipisicing elit. Minus, voluptas. Nam cupiditate non fugiat
    unde inventore, nobis illo distinctio id voluptatum amet ullam officia rem
    aspernatur provident facilis nulla dolores!"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import ServiceProvided from "../molecules/ServiceProvided.vue"

export default defineComponent({
  components: {
    ServiceProvided
  }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
  margin-left: 30px;
  margin-right: 50px;
}
</style>
