<template>
  <section id="skills" class="container mx-auto mt-20 md:mt-40">
    <div>
      <h2 class="text-center border-solid text-5xl md:text-6xl px-5 py-2 font-bold mb-4">Skills</h2>
      <div class="text-center">
        <p class="text-xl px-10 md:text-2xl font-bold">
          The skills, tools and technologies that I studied
        </p>
        <div
          class="grid grid-cols-3 lg:grid-cols-6 gap-12 w-1/2 mx-auto mt-10"
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
          <div class="flex align-middle justify-center hover:scale-125 duration-200">
            <img
              class="w-60"
              src="https://raw.githubusercontent.com/devicons/devicon/ca28c779441053191ff11710fe24a9e6c23690d6/icons/python/python-original.svg"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
