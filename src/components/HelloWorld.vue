<template>
  <div class="hello">
    <div class="viewport">{{ msg }}</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.viewport {
  width: 375px;
  height: 667px;
  background: #cccccc;
  font-size: 30px;
  border-bottom: 1px solid red;
}
</style>
