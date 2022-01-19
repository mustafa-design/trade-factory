<template>
  <div id="scroll-top-btn">
      <a onclick="topFunction()" id="myBtn">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6"
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
export default {

}
</script>

<style>
#myBtn {
    position: fixed;
    bottom: 40px;
    right: 40px;
    z-index: 100;
    background-color: #3cc3c1;
    border-radius: 50%;
    color: #fff;
    width: 50px;
    height: 50px;
    text-align: center;
    line-height: 3;
    cursor: pointer;
    opacity: 0.7;
    transition: 0.35s;
}
#myBtn:hover {
    opacity: 1;
}
</style>