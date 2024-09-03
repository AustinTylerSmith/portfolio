<script setup>
import {ref} from "vue";

let linkedinClass = ref('header-image')
let githubClass = ref('header-image')
let emailClass = ref('header-image')
let resumeClass = ref('header-image')

function clickedLinkedin() {
  linkedinClass.value = 'clicked-image'
  setTimeout(() => {
    linkedinClass.value = 'header-image'
  }, 200)
}
function clickedGithub() {
  githubClass.value = 'clicked-image'
  setTimeout(() => {
    githubClass.value = 'header-image'
  }, 200)
}
function clickedEmail() {
  emailClass.value = 'clicked-image'
  setTimeout(() => {
    emailClass.value = 'header-image'
  }, 200)
  window.location.href = "mailto:atylersmith@outlook.com"
}
function clickedResume() {
  resumeClass.value = 'clicked-image'
  setTimeout(() => {
    resumeClass.value = 'header-image'
  }, 200)
}
</script>

<template>
  <div class="flex justify-content-evenly align-items-center header-container">
    <a href="https://www.linkedin.com/in/austin-tyler-smith/" target="_blank"><img :class="linkedinClass" @click="clickedLinkedin" src="../assets/linkedin.png" alt="Linkedin"></a>
    <a href="https://github.com/AustinTylerSmith" target="_blank"><img :class="githubClass" @click="clickedGithub" src="@/assets/githubIcon.png" alt="GitHub"></a>
    <img :class="emailClass + ' email-hover'" @click="clickedEmail" src="@/assets/email.png" alt="Email">
    <a href="./../../src/assets/SMITH_AUSTIN_RESUME.docx.pdf" target="_blank"><img :class="resumeClass" @click="clickedResume" src="@/assets/resumeIcon.png" alt="Resume"></a>
  </div>
</template>

<style scoped>
.header-image {
  max-width: 50px;
}

.email-hover {
  cursor: pointer;
}

.clicked-image {
  width: 70px;
  max-width: 75px;
}

.header-container {
  background-color: #D3F4FF;
  border-bottom: 3px solid white;
  height: 5rem;
  position: fixed;
  top: 0;
  width: 100%;
  left: 0;
}
</style>