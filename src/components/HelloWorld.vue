<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="box">
    <h1>{{ msg }} 1111</h1>
  </div>
</template>

<style lang="less" scoped>
.box {

}
</style>
