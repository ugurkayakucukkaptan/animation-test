<template>
  <div class="container">
    <div class="wrapper" id="ahab"></div>
  </div>
</template>

<script>
import { init } from "animation-sdk/animations/confetti/confetti";
import "animation-sdk/animations/confetti/styles.css";
import { onMounted } from "@vue/runtime-core";
export default {
  setup() {
    onMounted(async () => {
      await init("ahab");
    });
  },
};
</script>

<style></style>
