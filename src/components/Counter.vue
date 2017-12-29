<template>
  <div>
    <h2>Count: {{ count }}</h2>

    <button @click="count += 1">Increment</button>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        count: 0
      }
    }
  }
</script>

<style>
</style>
