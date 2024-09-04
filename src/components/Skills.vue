<script setup>
import ProgressBar from "@/components/ProgressBar.vue";
import {ref} from "vue";

let clicked = ref(false)

let javascriptStrength = ref(0)
let typescriptStrength = ref(0)
let vueStrength = ref(0)
let responsivenessStrength = ref(0)
let htmlStrength = ref(0)
let cssStrength = ref(0)
let junitStrength = ref(0)
let vitestStrength = ref(0)
let playwrightStrength = ref(0)
let cypressStrength = ref(0)
let javaStrength = ref(0)
let springStrength = ref(0)
let jestStrength = ref(0)
let figmaStrength = ref(0)
let sqlStrength = ref(0)
let thymeleafStrength = ref(0)
let h2Strength = ref(0)
let dockerStrength = ref(0)
let podmanStrength = ref(0)
let reactStrength = ref(0)

function fireStrength() {
  clicked.value = true
  typescriptStrength.value = 99;

  setTimeout(() => {
    javascriptStrength.value = 99;
  }, 500)

  setTimeout(() => {
    vueStrength.value = 99;
  }, 1000)

  setTimeout(() => {
    responsivenessStrength.value = 99;
  }, 1500)

  setTimeout(() => {
    htmlStrength.value = 99
  }, 2000)

  setTimeout(() => {
    cssStrength.value = 99
  }, 2500)

  setTimeout(() => {
    junitStrength.value = 99
  }, 3000)

  setTimeout(() => {
    vitestStrength.value = 99
  }, 3500)

  setTimeout(() => {
    playwrightStrength.value = 99
  }, 4000)

  setTimeout(() => {
    cypressStrength.value = 99
  }, 4500)

  setTimeout(() => {
    javaStrength.value = 99
  }, 5000)

  setTimeout(() => {
    springStrength.value = 99
  }, 5500)

  setTimeout(() => {
    jestStrength.value = 99
  }, 6000)

  setTimeout(() => {
    figmaStrength.value = 90
  }, 6500)

  setTimeout(() => {
    sqlStrength.value = 90
  }, 7000)

  setTimeout(() => {
    thymeleafStrength.value = 90
  }, 7500)

  setTimeout(() => {
    h2Strength.value = 90
  }, 8000)

  setTimeout(() => {
    dockerStrength.value = 75
  }, 8500)

  setTimeout(() => {
    podmanStrength.value = 75
  }, 9000)

  setTimeout(() => {
    reactStrength.value = 75
  }, 9500)

}
</script>

<template>
  <div class="skill-width flex flex-column align-items-center mt-2">
    <header class="skills-header">Skills</header>
    <div class="flex flex-column justify-content-center skills-container" @mouseover="fireStrength" @click="fireStrength">
      <div class="flex justify-content-center pl-7">
        <span class="flex justify-content-center align-items-center strength">STRENGTH</span>
      </div>
      <div class="scroll-content flex flex-column">
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Typescript</span>
          <ProgressBar class="progress-width" :value="typescriptStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Javascript</span>
          <ProgressBar class="progress-width" :value="javascriptStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Vue.js</span>
          <ProgressBar class="progress-width" :value="vueStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Responsive Design</span>
          <ProgressBar class="progress-width" :value="responsivenessStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">HTML</span>
          <ProgressBar class="progress-width" :value="htmlStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">CSS</span>
          <ProgressBar class="progress-width" :value="cssStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Junit</span>
          <ProgressBar class="progress-width" :value="junitStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Vitest</span>
          <ProgressBar class="progress-width" :value="vitestStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Playwright</span>
          <ProgressBar class="progress-width" :value="playwrightStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Cypress</span>
          <ProgressBar class="progress-width" :value="cypressStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Java</span>
          <ProgressBar class="progress-width" :value="javaStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Spring Boot</span>
          <ProgressBar class="progress-width" :value="springStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Jest</span>
          <ProgressBar class="progress-width" :value="jestStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Figma</span>
          <ProgressBar class="progress-width" :value="figmaStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">SQL</span>
          <ProgressBar class="progress-width" :value="sqlStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Thymeleaf</span>
          <ProgressBar class="progress-width" :value="thymeleafStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">H2</span>
          <ProgressBar class="progress-width" :value="h2Strength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Docker</span>
          <ProgressBar class="progress-width" :value="dockerStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">Podman</span>
          <ProgressBar class="progress-width" :value="podmanStrength"/>
        </div>
        <div class="flex align-items-center justify-content-end">
          <span class="skill-type">React.js</span>
          <ProgressBar class="progress-width" :value="reactStrength"/>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.skill-width {
  width: 100vw;
}
.progress-width {
  width: 65% !important;
}
.scroll-content {
  padding-right: 2rem;
  overflow-y: scroll;
  scrollbar-width: thin;
  scrollbar-color: gray #FC9C1E;
}

.skill-type {
  font-size: 16px;
}

.skills-header {
  font-size: 50px;
}

.skills-container {
  background-color: #FC9C1E;
  border: 3px solid white;
  border-radius: 90px 90px 90px 90px;
  box-shadow: 2px 4px 6px rgba(0, 0, 0, 0.3);
  height: 60rem;
  padding: 2rem 0 2rem 2rem;
  overflow: hidden;
  width: 80%;
  max-width: 36rem;
}

.strength {
  width: fit-content;
  font-size: 20px;
  border-bottom: 2px solid white;
}
</style>