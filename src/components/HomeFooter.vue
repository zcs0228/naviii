<script setup lang="ts">
import { NButton } from "naive-ui";

const openProject = () => {
  window.open("https://github.com/eehhh/naviii");
};
</script>

<template>
  <span class="footer">
    <n-button
      class="project"
      strong
      secondary
      type="tertiary"
      size="large"
      @click="openProject"
    >
      Powered by 🛰️naviii
    </n-button>
  </span>
</template>

<style scoped>
.footer {
  display: flex;
  position: absolute;
  bottom: 0vh;
  bottom: -1vh;
  justify-content: center;
  align-items: center;
  margin: 10px 0px;
  padding: 0px 20px;
  width: 100%;
  z-index: 100;
}
.project {
  height: 30px;
  font-size: 12px;
}
</style>
