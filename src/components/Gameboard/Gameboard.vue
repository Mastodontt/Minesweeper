<script setup lang="ts">
import { defineAsyncComponent } from 'vue'

const GameHeader = defineAsyncComponent(() => import('@/components/GameHeader/GameHeader.vue'))
const GameContainer = defineAsyncComponent(
  () => import('@/components/GameContainer/GameContainer.vue'),
)
</script>
<template>
  <div class="gameboard">
    <GameHeader />
    <GameContainer />
  </div>
</template>

<style scoped>
.gameboard {
  background-color: grey;
  width: 800px;
  height: 500px;
  display: flex;
  flex-direction: column;
  padding:20px;
}
</style>
