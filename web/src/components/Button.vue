<script setup>
import { defineProps, defineEmits } from "vue";

const props = defineProps(["text"]);
// const emits = defineEmits(["click"]);
</script>

<template>
  <div id="discord-button">
    {{ props.text }}
  </div>
</template>

<style scoped>
#discord-button {
  width: calc(100% - 32px);
  background: #5864f2;
  font-size: 16px;
  line-height: 24px;
  padding: 10px 16px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  border: none;
  border-radius: 3px;
  font-family: "gg sans", "Noto Sans", "Helvetica Neue", Helvetica, Arial,
    sans-serif;
  cursor: pointer;
}
#discord-button:hover {
  background: #4751c4 !important;
}
</style>
