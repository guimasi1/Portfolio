<template>
  <section id="about" class="container mx-auto md:mt-20">
    <div>
      <h2 class="text-center border-solid text-5xl md:text-6xl rounded-lg px-5 py-2 font-bold mb-4">
        About me
      </h2>
      <div class="grid grid-cols-6 mt-10 md:mt-20">
        <div
          class="col-span-6 md:col-span-3 flex justify-center relative"
          v-motion
          :initial="{ opacity: 0, y: 50 }"
          :visibleOnce="{ opacity: 1, y: 0, transition: { duration: 700, delay: 400 } }"
        >
          <img
            class="mt-2 md:me-10 rounded-full border-4"
            src="../assets/avataaars (1).svg"
            alt="placeholder"
          />
          <div
            class="border-2 border-lime-500 rounded-xl px-6 pt-1 pb-2 absolute container-icons flex flex-col z-1 bg-gradient-to-r from-teal-200 to-teal-500"
          >
            <p class="font-bold text-black">Guido Masi</p>
            <div class="flex justify-center gap-4">
              <a href="https://github.com/guimasi1" class="w-5" rel="nofollow" target="_blank">
                <img src="../assets/github-icon-1.svg" alt="github"
              /></a>
              <a
                class="w-5"
                href="https://www.linkedin.com/in/guido-masi-fullstack-dev/"
                rel="nofollow"
                target="_blank"
              >
                <img src="../assets/linkedin-icon-1.svg" alt="linkedin"
              /></a>
            </div>
          </div>
        </div>
        <div
          class="text-lg mt-14 px-10 md:px-4 col-span-6 md:col-span-3 flex flex-col justify-center text-justify"
          v-motion
          :initial="{ opacity: 0, y: 50 }"
          :visibleOnce="{ opacity: 1, y: 0, transition: { duration: 500, delay: 600 } }"
        >
          <p>
            After working as a physiotherapist, my desire to assist people on a larger scale steered
            me towards the field of <strong>web development</strong>. Consequently, I enrolled in a
            course at EPICODE school, dedicating myself to studying day and night for 6 months. My
            journey has been fueled by an enduring <strong>curiosity</strong> and a strong
            <strong>work ethic</strong> that has always characterized me.
          </p>
          <p class="mt-2">
            For the final project in EPICODE, I developed a
            <a
              href="https://github.com/guimasi1/FRONTEND_FINAL_PROJECT"
              rel="nofollow"
              class="text-cyan-700 font-bold"
              target="_blank"
              >physiotherapy website</a
            >, merging my skills in web development with my professional background to create a
            resource aimed at helping others.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.container-icons {
  bottom: -10px;
  right: 42%;
}
</style>
