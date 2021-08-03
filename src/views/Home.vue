<template>
  <div>
    <top-navigation-bar></top-navigation-bar>
    <header-component></header-component>
  </div>
</template>

<script>
import TopNavigationBar from "@/components/TopNavigationBar.vue";
import HeaderComponent from "./components/Header.vue";
export default {
  name: "homepage",
  components: { TopNavigationBar, HeaderComponent }
};
</script>

<style></style>
