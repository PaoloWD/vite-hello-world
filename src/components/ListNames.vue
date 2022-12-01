<template>
  <h1>Stampo una lista v-for da un component</h1>
  <div class="d-flex">
    <div class="flex-column">
      <div class="bg-success px-3" v-for="(user, i) in usersList">
        {{ user.name }}
      </div>
    </div>
    <div class="flex-column flex-grow-1">
      <div class="bg-danger px-3" v-for="(user, i) in usersList">
        {{ user.name }} {{ user.surname }} {{ user.hello }}
      </div>
    </div>
    <div class="flex-column">
      <div class="bg-primary px-3" v-for="(user, i) in usersList">
        {{ user.surname }}
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      usersList: [
        {
          name: "Paolo",
          surname: "Lo Re",
          hello: "La mia prima app con Vite",
        },
        {
          name: "Giovanni",
          surname: "Licandro",
        },
        {
          name: "Luca",
          surname: "Gozzo",
        },
      ],
    };
  },
};
</script>
<style lang=""></style>
