<template>
  <BannerComponent />
  <FoundingComponent />
  <GrowthComponent />
  <TeamComponent />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BannerComponent from '@/components/about/BannerComponent.vue';
import FoundingComponent from '@/components/about/FoundingComponent.vue';
import GrowthComponent from '@/components/about/GrowthComponent.vue';
import TeamComponent from '@/components/about/TeamComponent.vue';

export default defineComponent({
  name: "AboutComponent",
  components: {
    BannerComponent,
    FoundingComponent,
    GrowthComponent,
    TeamComponent
  }
})

</script>

<style lang="scss" scoped>

</style>

