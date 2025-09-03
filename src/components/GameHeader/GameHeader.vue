<script setup lang="ts"></script>

<template>
  <div class="game-header">
    <div class="counter">12</div>
    <div class="smile">(.__.)</div>
    <div class="counter">12</div>
  </div>
</template>

<style scoped>
.game-header {
  display: flex;
  justify-content: space-between;
}

.smile {
  width: 50px;
  height: 50px;
  background-color: white;
  border-radius: 5px;
  border-color: rgb(0, 128, 128);
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
