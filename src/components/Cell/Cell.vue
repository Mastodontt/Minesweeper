<script setup lang="ts"></script>

<template>
  <div class="cell"></div>
</template>

<style scoped>
.cell {
  width: 20px;
  height: 20px;
  background-color: rgb(192, 192, 192);
  cursor: pointer;

  border-top: 2px solid white;
  border-left: 2px solid white;
  border-right: 2px solid rgb(128, 128, 128);
  border-bottom: 2px solid rgb(128, 128, 128);
}

.cell-revealed {
  background-color: rgb(222, 222, 222);
  border: 1px solid rgb(128, 128, 128);
  cursor: default;
}
</style>
