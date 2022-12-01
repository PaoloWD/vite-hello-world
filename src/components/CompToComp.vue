<template lang="">
  <div>
    <div class="text-center">
      <h1>Prendo un component da un altro component</h1>
      <ul>
        <li>
          <a href="" @click="onClickAlert"
            >Il css di questo file non vede nè il css dell'altro file nè il
            js</a
          >
        </li>
      </ul>
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
