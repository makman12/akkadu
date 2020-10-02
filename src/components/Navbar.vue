<template>
  <div class="main">
    <h1>{{ deneme }}</h1>
    <button @click="add()">add</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      deneme: 1,
    };
  },
  methods: {
    add() {
      this.deneme++;
    },
  },
};
</script>

<style>
button {
  padding: 1%;
  border: solid rebeccapurple;
}

.main {
  display: flex;
  justify-content: space-around;
  flex-direction: column;
  align-content: space-around;
}
</style>
