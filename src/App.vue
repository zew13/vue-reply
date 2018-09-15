<template lang="pug">
#app
  reply(placeholder="请输入 … ")
</template>

<script>
import reply from "./components/reply";

export default {
  name: "App",
  components: {
    reply
  }
};
</script>

<style>
textarea{
  font-size:16px;
  padding:16px;
  box-sizing:border-box;
}
</style>
