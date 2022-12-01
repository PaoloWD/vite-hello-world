<script>
import ListNames from "./components/ListNames.vue";
import SayGoodbye from "./components/SayGoodbye.vue";
import Navbar from "./components/Navbar.vue";
export default {
  components: { ListNames, SayGoodbye, Navbar },
  data() {
    return {};
  },
};
</script>

<template>
  <div class="container text-center">
    <Navbar></Navbar>
    <ListNames></ListNames>
    <SayGoodbye></SayGoodbye>
  </div>
</template>

<style scoped></style>
