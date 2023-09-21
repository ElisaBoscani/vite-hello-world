<script>
import AppTitol from "./components/AppTitol.vue";
export default {
  data() {
    return {
      message: "Hello Vite",
    };
  },
  components: {
    AppTitol,
  },
};
</script>

<template>
  <h1>{{ message }}</h1>
  <AppTitol />
</template>

<style></style>
