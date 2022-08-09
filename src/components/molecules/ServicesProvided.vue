<template>
  <div class="services-provided">
    <ServiceItem title="Front End" description="" />
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor unde eum
    impedit et harum modi amet, voluptatibus odit, molestias error tempora
    dolore nemo quod vitae, at a ab mollitia ipsum.
    <ServiceItem title="Back End" description="" />
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor unde eum
    impedit et harum modi amet, voluptatibus odit, molestias error tempora
    dolore nemo quod vitae, at a ab mollitia ipsum.
    <ServiceItem title="Manutenção" description="" />
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor unde eum
    impedit et harum modi amet, voluptatibus odit, molestias error tempora
    dolore nemo quod vitae, at a ab mollitia ipsum.
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import ServiceItem from "@/components/atoms/ServiceItem.vue"

export default defineComponent({ components: { ServiceItem } })
</script>

<style lang="scss" scoped></style>
