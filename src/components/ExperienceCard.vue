<script setup lang="ts">
defineProps<{ projectTitle: string, description: string, skills: string[], projectTime: number }>()
</script>

<template>
  <div class="flex flex-column project-exp mt-3 mb-2">
    <div class="flex justify-content-between mb-2">
      <span class="project-header">{{ projectTitle }}</span>
      <div class="flex pr-7 project-time"><span>{{ projectTime + ' Months'}}</span></div>
    </div>
    <div >
      <span class="we-content">{{ description }}</span>
    </div>
    <div class="flex flex-wrap">
      <span v-for="(skill, index) in skills" :key="index" class="skill">{{ skill }}</span>
    </div>
  </div>
</template>

<style scoped>
.project-time {
  font-size: 18px;
  font-weight: bolder;
  color: white;
}

.skill {
  border: 1px solid black;
  border-radius: 90px 90px 90px 90px;
  background-color: #D3F4FF;
  color: black;
  padding: .5rem;
  box-shadow: 2px 4px 6px rgba(0, 0, 0, 0.3);
  margin-right: .5rem;
  margin-top: .5rem;
  width: fit-content;
}

.project-header {
  font-size: 20px;
  font-weight: bolder;
  color: white;
}

.we-content {
  font-size: 18px;
  color: white;
  margin-bottom: .5rem;
}

.project-exp {
  border: 3px solid white;
  background-color: #7A88FF;
  padding: 1rem;
  border-radius: 0 90px 90px 0;
  box-shadow: 2px 4px 6px rgba(0, 0, 0, 0.3);
}
</style>