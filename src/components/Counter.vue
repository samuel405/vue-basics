<template>
  <h1>{{ count }}</h1>
  <button @click="increment">+</button>
  <button @click="decrement">-</button>
</template>

<script>
export default {
  name: "Counter",
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    increment() {
      this.count += 1;
    },
    decrement() {
      this.count = this.count > 0 ? this.count - 1 : this.count;
    },
  },
};
</script>

<style scoped>
button {
  margin-right: 1px;
  width: 20px;
  text-align: center;
}
</style>
