<script>
import ListNames from "./components/ListNames.vue";
import Navbar from "./components/Navbar.vue";
import CompToComp from "./components/CompToComp.vue";
import AppHero from "./components/AppHero.vue";
import AppTitle from "./components/AppTitle.vue";
export default {
  components: { ListNames, Navbar, CompToComp, AppHero, AppTitle },
  data() {
    return {};
  },
};
</script>

<template>
  <div class="container text-center">
    <AppTitle></AppTitle>
    <Navbar></Navbar>
    <ListNames></ListNames>
    <CompToComp></CompToComp>
    <AppHero></AppHero>
  </div>
</template>

<style scoped></style>
