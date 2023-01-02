<template>
  <div id="app">
    <Hash />
    <About />
  </div>
</template>

<script>
import Hash from "./components/nav.vue";
import About from "./components/about.vue";

export default {
  name: "App",
  components: {
    Hash,
    About,
  },
};
</script>

<style></style>
