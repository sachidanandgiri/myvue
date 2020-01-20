<template>
  <div>
    <h1>Counter</h1>
    <button @click="Incrememnt">Increment</button>
    {{ counter }}
    {{ doubCounter }}
  </div>
</template>

<script>
export default {
  data() {
    return {
      counter: 10,
      doubCounter: 0
    };
  },
  methods: {
    Incrememnt() {
      this.counter++;
      this.doubCounter = this.counter + 2;
    }
  }
};
</script>
