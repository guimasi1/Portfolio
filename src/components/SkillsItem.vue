<template>
  <div id="skills" class="container mx-auto mt-40">
    <div>
      <p class="text-center border-solid text-6xl px-5 py-2 font-bold mb-4">Skills</p>
      <div class="text-center">
        <p class="text-2xl font-bold">The skills, tools and technologies that I studied</p>
        <div
          class="grid sm:grid-cols-4 lg:grid-cols-6 gap-12 w-1/2 mx-auto mt-10"
          v-motion
          :initial="{ opacity: 0 }"
          :visibleOnce="{ opacity: 1, transition: { duration: 1000 } }"
        >
          <div class="flex align-middle hover:scale-125 duration-200">
            <img src="../assets/git-icon.svg" alt="" />
          </div>
          <div class="flex justify-center align-middle hover:scale-125 duration-200">
            <img src="../assets/bootstrap-5-1.svg" alt="" />
          </div>
          <div class="flex justify-center align-middle hover:scale-125 duration-200">
            <img class="" src="../assets/css-3.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img class="" src="../assets/html-1.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/java-icon.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/React-icon.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/redux.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/spring-3.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/tailwind-css-2.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/Unofficial_JavaScript_logo_2.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/vue-9.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img class="w-1/2" src="../assets/MongoDB_Logomark_ForestGreen.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/nodejs-icon.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/ts-logo-128.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/PostgreSQL_logo.3colors.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/visual-studio-code-1.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img src="../assets/jb_beam.svg" alt="" />
          </div>
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img class="w-2/3" src="../assets/Figma-logo.svg" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
