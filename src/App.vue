<template>
  <div>
    <MenuInicio />
  </div>
  <router-view />
</template>

<script>
import MenuInicio from "@/components/MenuPrincipal.vue";

export default {
  name: "MenuPrincipal",
  components: {
    MenuInicio,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 0;
}
</style>
