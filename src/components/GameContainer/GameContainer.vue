<script setup lang="ts">
import { defineAsyncComponent } from 'vue'
const Cell = defineAsyncComponent(() => import('@/components/Cell/Cell.vue'))
</script>

<template>
  <div class="game-container">
  </div>
</template>

<style scoped>
.game-container{
display: flex;
  border: 2px solid rgba(128, 128, 128, 0.055);
}

</style>
