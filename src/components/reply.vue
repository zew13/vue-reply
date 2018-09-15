<template lang="pug">
  textarea(:placeholder="placeholder")
</template>

<script>
export default {
  name: "reply",
  props: ["placeholder"],
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
textarea {
  resize: none;
  outline: 0;
  width: 100%;
  height: 80px;
}
</style>
