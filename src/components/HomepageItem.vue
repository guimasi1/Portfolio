<template>
  <section id="home" class="container grid md:grid-cols-6 md:mt-20 mx-auto">
    <div
      class="col-span-3 me-5 md:me-0 text-center md:text-start md:px-10 flex-column mt-10 ms-10 md:mt-0 md:pt-28 xl:pt-52"
    >
      <h1
        class="font-bold text-5xl md:text-6xl"
        v-motion
        :initial="{ opacity: 0, y: 50 }"
        :visibleOnce="{ opacity: 1, y: 0, transition: { duration: 200 } }"
      >
        Hi, I'm
      </h1>
      <h1
        class="font-bold mb-4 md:mb-0 text-6xl md:text-7xl text-cyan-400"
        v-motion
        :initial="{ opacity: 0, y: 50 }"
        :visibleOnce="{ opacity: 1, y: 0, transition: { duration: 500 } }"
      >
        Guido Masi,
      </h1>
      <p class="mt-2 text-xl md:text-2xl">
        a passionate Fullstack Developer with a background as a Physiotherapist.
      </p>
    </div>
    <div class="col-span-3">
      <img
        v-motion
        :initial="{ opacity: 0, y: 50 }"
        :visibleOnce="{ opacity: 1, y: 0, transition: { duration: 500 } }"
        class="rounded-full md:ms-12"
        src="../assets/penguin-using-laptop.png"
        alt="cartoon penguin working on a laptop"
      />
    </div>
  </section>
</template>
