<template>
  <input type="text">
</template>

<script>
export default {
  name: "HelloWorld",
inheritAttrs:false,
  props: {
    msg: String
  },
  created() {
    console.log(this.$attrs);
  }
};
</script>
<style scoped>
.green {
  color: green;
}
.red {
  color: red;
}
</style>