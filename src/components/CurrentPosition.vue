<script setup>
import Education from "@/components/Education.vue";
</script>

<template>
  <div class="current-position flex flex-column align-items-center mt-2">
    <header id="current-position-header">Current Position</header>
    <div class="cp-info-container mt-3 flex-column align-items-center justify-content-center mb-6">
      <div class="flex justify-content-center flex-1 mt-2 mb-2">
        <span class="job-title">Agile Developer at a Leading Publicly Traded Company</span>
      </div>
      <div class="flex small justify-content-between align-items-center">
        <span class="cp-header">Great American Insurance Group</span>
        <span class="flex-1 flex justify-content-end pr-4 years mt-1">August of 2022 - Present</span></div>
      <p class="mt-2 cp-content">
        With hands-on experience in an agile environment at a publicly traded company generating $7 billion in annual
        revenue, I’ve honed my expertise in delivering high-quality software solutions. My commitment to rigorous
        software development standards, including test-driven development, code reviews, version control, and promoting
        code readability, has been central to my role.
      </p>
      <p class="mt-2 cp-content">
        I spearheaded and managed a proof-of-concept project, driving alignment with key stakeholders and
        cross-functional teams, while collaborating seamlessly with over 10 teams across 6 business units. My role
        required a deep understanding of agile principles to meet the dynamic and evolving needs of the business.
      </p>
      <p class="mt-2 cp-content">
        Throughout my tenure, I acquired and applied new skills across 4 different projects, demonstrating adaptability
        and a commitment to continuous learning. I also played a pivotal role in implementing patches and introducing
        new functionalities across 7 unique applications, contributing to the company’s success in delivering robust and
        scalable software solutions.
      </p>
    </div>
    <Education/>
  </div>
</template>