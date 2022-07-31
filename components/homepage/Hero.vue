<template>
  <section class="container px-4 py-32 mx-auto bg-white bg-cover bg-center rounded-3xl" :style="{ backgroundImage: `url(${image})`}">
    <div class="w-full mx-auto text-center md:w-11/12 xl:w-8/12 " >
      <h1 class="mb-3 text-4xl font-bold text-gray-900 md:text-5xl md:leading-tight md:font-extrabold">Quantum Algorithms for a better future!</h1>
      <p class="mb-6 text-lg text-gray-800 md:text-xl md:leading-normal font-light py-5">
        By using maritime data we devolope quantum algorithms to tackle the biggest problems of our generation.
      </p>
      <button class="col-auto lg:col-span-2 bg-black text-white rounded-sm py-3 px-5 text-lg font-normal">Find out how!</button>
    </div>
  </section>
</template>

<script>
import bgHero from "assets/images/bg-hero.jpg";export default {
  data() {
    return {
      image: bgHero,    };
  }
};
</script>