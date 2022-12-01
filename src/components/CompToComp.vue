<template lang="">
  <div>
    <div class="text-center">
      <h1>Prendo un component da un altro component</h1>
    </div>
    <h2><ListNames></ListNames></h2>
  </div>
</template>
<script>
import ListNames from "./ListNames.vue";

export default {
  components: {
    ListNames,
  },
  data() {
    return {};
  },
};
</script>
<style lang=""></style>
