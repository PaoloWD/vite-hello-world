<script>
import ListNames from "./components/ListNames.vue";
import Navbar from "./components/Navbar.vue";
import CompToComp from "./components/CompToComp.vue";
export default {
  components: { ListNames, Navbar, CompToComp },
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
  </div>
</template>

<style scoped></style>
