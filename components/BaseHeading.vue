<template>
  <h2 class="font-sans text-lg text-gray-800 text-center text-3xl mb-10">
    <slot />
  </h2>
</template>

<script>
/** export 書き出す */
  export default {
    name: 'BaseHeading',
  }
</script>

<style scoped>
  /* h2 {
    font-size: 30px;
    font-weight: bold;
  } */
</style>

