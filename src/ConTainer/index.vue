<template>
<div class="container">
  <slot></slot>
</div>
</template>

<script>
export default {
  name: "ConTainer"
}
</script>

<style scoped>
.container {
  width: 90%;
  margin: 0 auto;
}
</style>