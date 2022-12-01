<script>
import ListNames from "./components/ListNames.vue";
import Navbar from "./components/Navbar.vue";
import CompToComp from "./components/CompToComp.vue";
import Jumbotron from "./components/Jumbotron.vue";
export default {
  components: { ListNames, Navbar, CompToComp, Jumbotron },
  data() {
    return {};
  },
};
</script>

<template>
  <div class="container text-center">
    <Navbar></Navbar>
    <ListNames></ListNames>
    <CompToComp></CompToComp>
    <Jumbotron></Jumbotron>
  </div>
</template>

<style scoped></style>
