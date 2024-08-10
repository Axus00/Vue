<template>
  <NavBarComponent />
  <router-view/>
  <FooterComponent />
</template>

<script lang="ts" setup>
import NavBarComponent from "./components/home/NavBarComponent.vue";
import FooterComponent from "./components/home/FooterComponent.vue";


</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
}

html{
  box-sizing: border-box;
}
</style>
