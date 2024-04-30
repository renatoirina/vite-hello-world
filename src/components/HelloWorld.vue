<script>
export default {
  data() {
    return {
      title: "Hello World!"
    };
  },
};
</script>

<template>
  <h1>{{ title }}</h1>
</template>

<style>
  h1 {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
</style>