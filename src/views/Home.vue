<template>
  <master-layout>
    <HeroSection />
    <VideoSection />
    <CoursesSection />
    <IconsSection />
    <TradeNowSection />
  </master-layout>
</template>

<script>
import HeroSection from "../components/HeroSection.vue";
import VideoSection from "../components/VideoSection.vue";
import CoursesSection from "../components/CoursesSection.vue";
import IconsSection from "../components/IconsSection.vue";
import TradeNowSection from "../components/TradeNowSection.vue";
import MasterLayout from './Layouts/Master.vue'

export default {
  name: "Home",
  components: {
    MasterLayout,
    HeroSection,
    VideoSection,
    CoursesSection,
    IconsSection,
    TradeNowSection
  },
};
</script>