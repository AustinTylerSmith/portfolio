<script setup lang="ts">
defineProps<{value: number}>()
</script>

<template>
  <div class="progress-bar-container">
    <div class="progress-bar flex align-items-center justify-content-center"
         :style="{width: `${value}%`}">{{ value > 30 ? value + '/100' : ''  }}</div>
  </div>
</template>

<style scoped>
.progress-bar-container {
  width: 15rem;
  background-color: #e0e0e0;
  border-radius: 10px;
  overflow: hidden;
  height: 20px; /* Adjust height as needed */
  margin: 1.5rem;
  margin-right: 0 !important;
}

.progress-bar {
  height: 100%;
  background-color: #4caf50; /* Progress bar color */
  width: 0;
  transition: width 0.4s ease-in-out;
}
</style>