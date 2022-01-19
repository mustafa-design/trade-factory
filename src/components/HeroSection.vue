<template>
  <section
    class="
      hero
      relative
      bg-[url('https://traderfactory.com/wp-content/uploads/2021/05/home-slider-2.jpg')]
      bg-cover
    "
  >
    <div
      class="overlay h-full w-full absolute top-0 left-0 bg-[#2B2B2D] opacity-80 z-10"
    ></div>
    <HeroContent />
  </section>
</template>

<script>
import HeroContent from "./HeroContent.vue";
export default {
  // name: 'HeroSection',
  components: { HeroContent },
};
</script>

<style>
</style>