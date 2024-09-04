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
    'I worked on a Billing Management System used by both employees and insureds, streamlining billing processes for enhanced efficiency and user satisfaction.'"
          :skills="['Java', ' Spring Boot', ' Junit', ' Typescript', ' Vue3', ' Vitest', ' Playwright']"
          :project-time="5"
      />
      <ExperienceCard
          :project-title="'Policy Sweet'"
          :description="
    'My Team and I developed the external-facing Policy Sweet Quoter Application, integrating essential company services while prioritizing a top-tier user experience.'"
          :skills="['Java', ' Spring Boot', ' Junit', ' Typescript', ' Vue3', ' Vitest', ' Playwright']"
          :project-time="5"
      />
      <ExperienceCard
          :project-title="'Collateral Management'"
          :description="
    'I enhanced a Collateral Management Application at an insurance company, focusing on optimizing the front-end to ' +
     'streamline asset tracking and improve compliance and risk management.'"
          :skills="['Java', ' Spring Boot', ' Typescript', ' Vue2', ' Jest', ' Cypress']"
          :project-time="5"
      />
      <ExperienceCard
          :project-title="'Unqork Proof of Concept'"
          :description="
    'I explored the Unqork No Code/Low Code platform to evaluate its potential integration with our company\'s core ' +
     'practices, focusing on its adaptability and effectiveness for rapid development.'"
          :skills="['Unqork', ' Angular', ' CSS', ' HTML']"
          :project-time="4"
      />
      <ExperienceCard
          :project-title="'Risk Analysis Tool'"
          :description="
    'I worked on a Risk Analyses Tool used by over 1,000 underwriters to gain crucial insights for informed policy decisions.'"
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