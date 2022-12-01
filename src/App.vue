<script>
import SayHello from "./components/SayHello.vue";
import SayGoodbye from "./components/SayGoodbye.vue";
export default {
  components: { SayHello, SayGoodbye },
  data() {
    return {};
  },
};
</script>

<template>
  <div class="container text-center">
    <SayHello></SayHello>
    <SayGoodbye></SayGoodbye>
  </div>
</template>

<style scoped></style>
