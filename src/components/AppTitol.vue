<script>
export default {
  data() {
    return {
      titol: "La mia prima app con Vite!",
    };
  },
};
</script>

<template>
  <h1 class="titol">{{ titol }}</h1>
</template>

<style>
.titol {
  margin-bottom: 100px;
}
</style>
