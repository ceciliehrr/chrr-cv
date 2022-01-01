<template>
  <el-menu class="el-menu-vertical-demo" mode="vertical">
    <el-sub-menu index="1">
      <template #title>
        <el-icon><setting /></el-icon>
      </template>
      <el-menu-item-group title="Group One">
        <el-menu-item index="1-1">Fargekode 1 <Switch /></el-menu-item>
        <el-menu-item index="1-2">Fargekode 2 <Switch /></el-menu-item>
      </el-menu-item-group>
    </el-sub-menu>
  </el-menu>
</template>

<script lang="ts" setup>
import { Setting } from "@element-plus/icons-vue";
import Switch from "./Switch.vue";
</script>

<style>
.el-menu-vertical-demo:not(.el-menu--collapse) {
  width: 200px;
}
</style>