<template>
  <section class="bg-[#222] py-24">
    <div class="mx-auto w-[1140px]">
      <h4 class="text-4xl text-[#B7CF34]">دورات فوركس تدريبية</h4>
      <p class="text-white text-2xl my-3 tracking-wide leading-10">
        ابدأ رحلة احتراف التداول من أي مكان وفي أي وقت
      </p>
      <div class="line mx-auto my-8 bg-white width w-24 h-px"></div>
      <div class="flex flex-wrap">
        <CourseCard v-for="item in content" :item="item" :key="item.id" />
      </div>
    </div>
  </section>
</template>

<script>
import CourseCard from "./CourseCard.vue";

const content = [{
  id: 1,
  img_url:
    '"https://traderfactory.com/wp-content/uploads/2021/05/fundemental-analysis.jpg"',
  title: "القسم الثاني",
  description: "التحليل الأساسي في سوق العملات",
},
{
  id: 2,
  img_url:
    '"https://traderfactory.com/wp-content/uploads/2021/05/forex-intro-basics.jpg"',
  title: "القسم الثاني",
  description: "التحليل الأساسي في سوق العملات",
},
{
  id: 3,
  img_url:
    '"https://traderfactory.com/wp-content/uploads/2021/05/fundemental-analysis.jpg"',
  title: "القسم الثاني",
  description: "التحليل الأساسي في سوق العملات",
},
{
  id: 4,
  img_url:
    '"https://traderfactory.com/wp-content/uploads/2021/05/fundemental-analysis.jpg"',
  title: "القسم الثاني",
  description: "التحليل الأساسي في سوق العملات",
},
{
  id: 5,
  img_url:
    '"https://traderfactory.com/wp-content/uploads/2021/05/fundemental-analysis.jpg"',
  title: "القسم الثاني",
  description: "التحليل الأساسي في سوق العملات",
},
{
  id: 6,
  img_url:
    '"https://traderfactory.com/wp-content/uploads/2021/05/fundemental-analysis.jpg"',
  title: "القسم الثاني",
  description: "التحليل الأساسي في سوق العملات",
}];

export default {
  components: { CourseCard },
  setup() {
    return {
      content
    }
  }
}
</script>

<style>
</style>