<script>
import AppTitol from "./components/AppTitol.vue";
import AppHero from "./components/AppHero.vue";
export default {
  data() {
    return {
      message: "Hello Vite",
    };
  },
  components: {
    AppTitol,
    AppHero,
  },
};
</script>

<template>
  <!-- <h1>{{ message }}</h1> -->
  <AppTitol />
  <AppHero />
</template>

<style></style>
