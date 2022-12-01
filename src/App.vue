<script>
import SayHello from "./components/SayHello.vue";
import SayGoodbye from "./components/SayGoodbye.vue";
import Navbar from "./components/Navbar.vue";
export default {
  components: { SayHello, SayGoodbye, Navbar },
  data() {
    return {};
  },
};
</script>

<template>
  <div class="container text-center">
    <Navbar></Navbar>
    <SayHello></SayHello>
    <SayGoodbye></SayGoodbye>
  </div>
</template>

<style scoped></style>
