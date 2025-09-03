<script setup lang="ts">
import { defineAsyncComponent } from 'vue'

const Gameboard = defineAsyncComponent(() => import('@/components/Gameboard/Gameboard.vue'))
</script>
<template>
  <div class="container">
    <div class="minesweeper">
      <Gameboard />
    </div>
  </div>
</template>

<style scoped>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 1200px;
  margin-left: auto;
  margin-right: auto;
}
</style>
