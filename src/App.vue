<script setup>
import WelcomePhoto from "@/components/WelcomePhoto.vue";
import AboutMeMessage from "@/components/AboutMeMessage.vue";
import WorkExperience from "@/components/WorkExperience.vue";
import CurrentPosition from "@/components/CurrentPosition.vue";
import Skills from "@/components/Skills.vue";
import ContactHeader from "@/components/ContactHeader.vue";
</script>

<template>
  <ContactHeader/>
  <div class="flex justify-content-evenly flex-wrap">
    <WelcomePhoto/>
    <AboutMeMessage/>
  </div>
  <div class="flex justify-content-evenly flex-wrap gap-4">
    <WorkExperience/>
    <CurrentPosition/>
  </div>
  <div class="flex flex-wrap justify-content-evenly">
    <Skills/>
  </div>
</template>
<style scoped>
.header {
  height: 7rem;
  background-color: gray;
}
</style>