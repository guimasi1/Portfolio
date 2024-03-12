<template>
  <section id="projects" class="container mx-auto mt-20 md:mt-40">
    <div class="flex flex-col">
      <h2 class="text-center text-5xl md:text-6xl px-5 py-2 font-bold mb-12">Last projects</h2>

      <div class="grid px-5 lg:grid-flow-col lg:gap-5">
        <article
          class="mb-10"
          v-motion
          :initial="{ opacity: 0, x: -80 }"
          :visibleOnce="{ opacity: 1, x: 0, transition: { duration: 900 } }"
        >
          <a
            href="https://github.com/guimasi1/FRONTEND_FINAL_PROJECT"
            rel="nofollow"
            target="_blank"
          >
            <div class="shadow-2xl rounded-3xl cursor-pointer pb-2 card-project">
              <img
                class="rounded-t-3xl image-card-project"
                src="../assets/physio-path.png"
                alt="physio-path github repository"
              />
              <p class="font-bold mt-4 mb-2 text-lg text-center">PhysioPath</p>
              <p class="px-5 mb-5 text-sm text-justify">
                A website designed to bridge the gap between physiotherapists and their patients.
                Through this platform, physiotherapists have the ability to assign specific
                exercises to their patients, who, in turn, can log in to access their personalized
                rehabilitation programs.
              </p>
            </div>
          </a>
        </article>
        <article
          class="mb-10"
          v-motion
          :initial="{ opacity: 0, y: 80 }"
          :visibleOnce="{ opacity: 1, y: 0, transition: { duration: 900 } }"
        >
          <a href="https://github.com/guimasi1/U3-W2-D5" rel="nofollow" target="_blank">
            <div class="shadow-2xl rounded-3xl cursor-pointer pb-2 card-project">
              <img
                class="rounded-t-3xl image-card-project w-full"
                src="../assets/weather-now.png"
                alt="weather-now github repository"
              />
              <p class="font-bold mt-4 mb-2 text-lg text-center">WeatherNow</p>
              <p class="px-5 mb-5 text-sm text-justify">
                I developed a user-friendly website that offers real-time weather updates at your
                fingertips. This platform allows users to quickly check current weather conditions,
                forecasts, pollution and meteorological trends for any location of their choice,
                with the possibility to add your favourite cities.
              </p>
            </div>
          </a>
        </article>
        <article
          class="mb-10"
          v-motion
          :initial="{ opacity: 0, x: 80 }"
          :visibleOnce="{ opacity: 1, x: 0, transition: { duration: 900 } }"
        >
          <a href="https://modestini-logopedia.netlify.app/" rel="nofollow" target="_blank">
            <div class="shadow-2xl rounded-3xl cursor-pointer pb-2 card-project">
              <img
                class="rounded-t-3xl image-card-project w-full"
                src="../assets/speech-therapist.png"
                alt="weather-now github repository"
              />
              <p class="font-bold mt-4 mb-2 text-lg text-center">Speech Therapist Website</p>
              <p class="px-5 mb-5 text-sm text-justify">
                I crafted a website for an individual speech therapist, aimed at showcasing their
                professional services and expertise in the field. This tailored platform highlights
                the therapist's qualifications and specialized approaches to speech therapy.
              </p>
            </div>
          </a>
        </article>
      </div>
    </div>
  </section>
</template>

<style>
.card-project {
  height: 450px;
}
.image-card-project {
  height: 220px;
}
</style>
