<template>
    <ApplicationComponent />
</template>
  
<script lang="ts">
  import ApplicationComponent from '@/components/contact/ApplicationComponent.vue';
  import { defineComponent } from 'vue';

  export default defineComponent({
    name: "ContactComponent",
    components: {
      ApplicationComponent
    }
  })

  
</script>
  
<style scoped>
  
</style>
  