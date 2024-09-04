<script setup>

</script>

<template>
    <img class="mb-2" id="main-photo" src="@/assets/MAIN_PIC.JPG" alt="profile_pic">
    <div class="flex flex-column align-items-center justify-content-center hello-message mb-2">
      <span class="hello-world">Hello World... I am</span>
      <span class="name mb-2">Austin Smith</span>
    </div>
</template>

<style scoped>
.name {
  border-top: 3px solid white;
  border-bottom: 3px solid white;
  font-size: 300%;
}

.hello-world {
  font-size: 200%;
  color-scheme: only light !important;
}


#main-photo {
  border-radius: 90px 90px 90px 90px;
  border: 3px solid white;
  width: 22%;
  min-width: 161px;
}
</style>