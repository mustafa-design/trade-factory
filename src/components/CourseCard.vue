<template>
  <div class="group card m-2">
    <div class="overflow-hidden">
      <div
        :class="[
          imageUrl(),
          'group-hover:scale-125 duration-500 bg-cover rounded-t h-[200px]',
        ]"
      ></div>
    </div>
    <div class="card-content text-white p-6">
      <h2 class="text-3xl text-[#B7CF34]">{{ this.item.title }}</h2>
      <p class="my-3 font-medium text-l">{{ this.item.description }}</p>
      <button
        class="
          py-2
          px-6
          border-2
          rounded
          border-white
          hover:border-[#B7CF34]
          font-semibold
        "
      >
        اقرأ المزيد
      </button>
    </div>
  </div>
</template>

<script>


export default {
  props: ['item'],
  methods: {
    imageUrl() {
      return "bg-[url(" + this.item.img_url + ")]";
    },
  },
}
</script>

<style>
.card {
  flex: 1 0 30%;
}
</style>