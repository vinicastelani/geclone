<template>
  <homepage></homepage>
</template>

<script>
import Homepage from "./views/Home.vue";
import "@/style/grid.css";
import "@/style/typo.css";
import "@/style/flex.css";
export default {
  name: "App",
  components: { Homepage }
};
</script>

<style>
html,
body {
  margin: 0;
}
</style>
