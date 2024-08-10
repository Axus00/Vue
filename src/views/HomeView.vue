<template>
  <div class="home">
    <BannerComponent />
    <InfoComponent />
    <TestimonialComponent />
    <CardsComponent />
    <FormComponent />
  </div>
</template>

<script lang="ts">
//importamos los componentes
import { defineComponent } from "vue";

import BannerComponent from "@/components/home/BannerComponent.vue";
import InfoComponent from "@/components/home/InfoComponent.vue";
import TestimonialComponent from "@/components/home/TestimonialComponent.vue";
import CardsComponent from "@/components/home/CardsComponent.vue";
import FormComponent from "@/components/home/FormComponent.vue";

export default defineComponent({
  name: "HomeComponent",
  components: {
    BannerComponent,
    InfoComponent,
    TestimonialComponent,
    CardsComponent,
    FormComponent
  }
})

</script>

<style scoped>

</style>
