<template>
  <div id="app">
    <div>
      <Navigation />
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
@import "assets/sass/main";
</style>

<script>
import Navigation from "@/components/Navigation.vue";

export default {
  name: "Home",
  components: { Navigation },
};
</script>
