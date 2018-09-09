<template>
  <div class="demo">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'First',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.demo {
  background-color: cyan;
}
</style>
