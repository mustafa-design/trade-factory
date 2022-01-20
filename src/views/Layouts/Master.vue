<template>
  <div class="font-['Cairo']">
    <Header />
    <slot></slot>
    <Footer />
    <ScrollTop />
  </div>
</template>

<script>
import Header from "../../components/Header";
import Footer from "../../components/Footer.vue";
import ScrollTop from "../../components/ScrollTop.vue";

export default {
  name: "Home",
  components: {
    Header,
    Footer,
    ScrollTop
  },
};
</script>