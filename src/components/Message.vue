<template>
  <div class="box">
    <p>
      <slot></slot>
    </p>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="scss">
  .box {
    background: #e3e3e3;
    border: 1px solid #c5c5c5;
    padding: 1em;
    margin-bottom: 1em;
  }
</style>
