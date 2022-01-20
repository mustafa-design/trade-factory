<template>
  <div id="scroll-top-btn">
    <a
      @click="topFunction"
      id="myBtn"
      class="
        fixed
        -bottom-12
        right-10
        z-[1000]
        text-white
        bg-[#B7CF34]
        rounded-md
        w-12
        h-12
        cursor-pointer
        opacity-70
        duration-500
        hover:opacity-100
      "
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-full w-6 mx-auto"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M5 15l7-7 7 7"
        />
      </svg>
    </a>
  </div>
</template>

<script>

window.addEventListener("scroll", function () {
    var mybutton = document.getElementById("myBtn");
  if (
    document.body.scrollTop > 300 ||
    document.documentElement.scrollTop > 300
  ) {
    mybutton.classList.remove("-bottom-12");
    mybutton.classList.add("bottom-10");
  } else {
    mybutton.classList.remove("bottom-10");
    mybutton.classList.add("-bottom-12");
  }
});

export default {
  methods: {
    topFunction() {
      document.documentElement.scrollTop = 0;
    },
  },
};
</script>

<style>
</style>