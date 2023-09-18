<script setup lang="ts">
import { NMessageProvider } from "naive-ui";
import HomeSider from "@/components/HomeSider.vue";
import HomeContent from "@/components/HomeContent.vue";
import HomeFooter from "@/components/HomeFooter.vue";
</script>

<template>
  <n-message-provider>
    <HomeSider />
    <HomeContent />
  </n-message-provider>
  <HomeFooter />
</template>

<style scoped></style>
