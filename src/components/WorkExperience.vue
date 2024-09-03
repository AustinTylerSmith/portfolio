<script setup>

import ExperienceCard from "@/components/ExperienceCard.vue";
</script>

<template>
  <div class="work-experience flex flex-column align-items-center mt-2">
    <header id="work-experience-header">Project Experience</header>
    <div class="flex flex-column align-content-start">
      <ExperienceCard
          :project-title="'My Billing'"
          :description="
    'Billing Management System used by employees and insureds.'"
          :skills="['Java', ' Spring Boot', ' Junit', ' Typescript', ' Vue3', ' Vitest', ' Playwright']"
          :project-time="5"
      />
      <ExperienceCard
          :project-title="'Policy Sweet'"
          :description="
    'Insurance quoter “Policy Sweet”. Integrated critical company services with the highest quality user experience.'"
          :skills="['Java', ' Spring Boot', ' Junit', ' Typescript', ' Vue3', ' Vitest', ' Playwright']"
          :project-time="5"
      />
      <ExperienceCard
          :project-title="'Collateral Management'"
          :description="
    'Application used to track Collateral for insureds.'"
          :skills="['Java', ' Spring Boot', ' Typescript', ' Vue2', ' Jest', ' Cypress']"
          :project-time="5"
      />
      <ExperienceCard
          :project-title="'Unqork Proof of Concept'"
          :description="
    'Proof of Concept to test usability of Low Code No Code platform.'"
          :skills="['Unqork', ' Angular', ' CSS', ' HTML']"
          :project-time="4"
      />
      <ExperienceCard
          :project-title="'Risk Analysis Tool'"
          :description="
    'Application leveraged by 1K+ underwriters who write policies. The RA Tool gives pivotal insight to the underwriter ' +
     'when making decisions on an insureds policy.'"
          :skills="['Unqork', ' Angular', ' CSS', ' HTML']"
          :project-time="5"
      />
    </div>
  </div>
</template>

<style scoped>
#work-experience-header {
  font-size: 50px;
}

.work-experience {
  width: 75rem;
}
</style>