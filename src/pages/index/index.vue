<template>
  <view class="content">
    <view class="text-area">
      <text class="title">{{ title }}</text>
    </view>
  </view>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const title = ref('CRM Mobile Demo')
</script>

<style>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 10px;
}

.text-area {
  display: flex;
  justify-content: center;
  padding: 20px;
  border: 3px solid goldenrod;
  border-radius: 12px;
}

.title {
  font-size: 36rpx;
  color: darkgrey;
}
</style>
