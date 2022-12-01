<template>
  <div>
    <h2>{{ getSayHello() }}</h2>
  </div>
</template>
<script>
export default {
  data() {
    return {
      hello: {
        sayHello: "Ciao Mondo",
      },
    };
  },
  methods: {
    getSayHello() {
      return this.hello.sayHello;
    },
  },
};
</script>
<style lang=""></style>
