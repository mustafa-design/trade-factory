<template>
  <div class="home">
    <Header />
    <HeroSection />
    <VideoSection />
    <CoursesSection />
    <IconsSection />
    <TradeNowSection />
    <Footer />
    <ScrollTop />
  </div>
</template>

<script>
import Header from "../components/Header";
import HeroSection from "../components/HeroSection.vue";
import VideoSection from "../components/VideoSection.vue";
import CoursesSection from "../components/CoursesSection.vue";
import IconsSection from "../components/IconsSection.vue";
import TradeNowSection from "../components/TradeNowSection.vue";
import Footer from "../components/Footer.vue";
import ScrollTop from "../components/ScrollTop.vue";

export default {
  name: "Home",
  components: {
    Header,
    HeroSection,
    VideoSection,
    CoursesSection,
    IconsSection,
    TradeNowSection,
    Footer,
    ScrollTop
  },
};
</script>