<script setup lang="ts">
import { NButton, NSpace, NGrid, NGi } from 'naive-ui';
</script>

<template>
  <div>
    <!-- <NuxtWelcome /> -->
    <!-- <n-button type="error"> Error </n-button> -->
    <n-grid x-gap="20" y-gap="36" cols="1 s:2 m:4" responsive="screen">
      <n-gi class="item">n-gi-1</n-gi>
      <n-gi class="item">n-gi-2</n-gi>
      <n-gi class="item">n-gi-3</n-gi>
      <n-gi class="item">n-gi-4</n-gi>
    </n-grid>
  </div>
</template>

<style scoped>
.item {
  border: 1px salmon solid;
  padding: 20px;
}
</style>
