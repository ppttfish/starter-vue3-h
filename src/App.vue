<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div>
    <van-grid column-num="2">
      <van-grid-item>
        <RouterLink to="/">首页</RouterLink>
      </van-grid-item>
      <van-grid-item>
        <RouterLink to="/about">About</RouterLink>
      </van-grid-item>
    </van-grid>
  </div>
  <RouterView />
</template>

<style scoped></style>
