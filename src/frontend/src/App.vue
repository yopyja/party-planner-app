<template>
  <div id="app">
    <Navigation />
    <router-view />
  </div>
</template>

<style lang="scss">
@import "assets/sass/main";
</style>

<script lang="ts">
import Navigation from "./components/Navigation.vue";

export default {
  name: "app",
  components: { Navigation },
};
</script>
