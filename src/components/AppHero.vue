<script>
export default {
  data() {
    return {
      message: "Hello Vite",
    };
  },
};
</script>

<template>
  <div>
    <h1>{{ message }}</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas sed
      impedit, dolorum, nostrum magni quos mollitia eius hic eum odio
      consequatur voluptates!
    </p>

    <a href="#">Learn more</a>
  </div>
</template>
<style>
div > div {
  background-color: bisque;
  padding: 30px;
  color: black;
}
a {
  background-color: aquamarine;
  padding: 10px;
  color: aliceblue;
}
</style>
