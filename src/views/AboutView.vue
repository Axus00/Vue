<template>
  <BannerComponent />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BannerComponent from '@/components/about/BannerComponent.vue';

export default defineComponent({
  name: "AboutComponent",
  components: {
    BannerComponent
  }
})

</script>

<style lang="scss" scoped>

</style>

