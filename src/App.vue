<template>
  <div id="app">
    <div id="nav">
      <router-link to="/login">Login</router-link> |
      <router-link to="/">Home</router-link> |
      <router-link to="/guest">Guest</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
@import "assets/sass/main";
</style>
