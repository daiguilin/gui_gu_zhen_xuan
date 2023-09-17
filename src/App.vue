<script setup lang="ts"></script>

<template>
  <div>
    <span>HelloWorld</span>
    <el-button type="primary" :icon="Edit" circle />
  </div>
</template>
<script setup lang="ts">
import { Edit } from '@element-plus/icons-vue'
console.log('import.meta.env',import.meta.env);

</script>

<style scoped></style>
