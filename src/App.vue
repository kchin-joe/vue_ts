<script setup lang="ts">
import { Edit } from '@element-plus/icons-vue'
import Test from '@/components/test.vue'
</script>

<template>
  <div class="box">
    <el-button type="primary" :icon="Edit">按钮</el-button>
    <Test></Test>
  </div>
</template>

<style scoped scss></style>
