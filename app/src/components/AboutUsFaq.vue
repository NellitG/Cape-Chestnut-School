<template>
  <section class="py-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-8">
      <div class="py-8 px-4 mx-auto max-w-7xl text-center lg:py-8 lg:px-0">
        <h1
          class="mb-4 text-3xl font-semibold tracking-tight leading-none text-secondary-color md:text-5xl"
        >
          Frequently Asked Questions
        </h1>
        <p
          class="mb-0 text-lg font-normal text-gray-950 lg:text-xl sm:px-16 xl:px-48"
        >
          Good Education, Good Character
        </p>
      </div>
      <div class="max-w-3xl mx-auto">
        <ul class="mt-0 divide-y-2 rounded-2xl">
          <li v-for="(faq, index) in faqs" :key="index">
            <details class="group">
              <summary
                @click="toggleAccordion(index)"
                class="flex items-center justify-between px-4 sm:px-8 py-3 font-medium hover:cursor-pointer"
              >
                <span class="font-semibold text-xl py-2">{{
                  faq.question
                }}</span>
                <span class="text-2xl">{{ faq.open ? "-" : "+" }}</span>
              </summary>

              <div v-show="faq.open" class="m-4 p-4 rounded-2xl text-gray-950">
                <p>
                  {{ faq.answer }}
                </p>
              </div>
            </details>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from "vue";

const faqs = ref([
  {
    question: " What age groups does the school cater to?",
    answer:
      "Cape Chestnut School offers educational programs for children from kindergarten through elementary grades. We are continuously expanding to accommodate different age groups and meet the needs of our community.",
    open: false,
  },
  {
    question: "What extracurricular activities are available for students?",
    answer:
      "We offer a variety of extracurricular activities, including art, music, sports, gardening, and a STEM program that encourages exploration and innovation in science, technology, engineering, and math.",
    open: false,
  },
  {
    question: "What is the student-to-teacher ratio at Cape Chestnut School?",
    answer:
      "We maintain a low student-to-teacher ratio to ensure personalized attention and support for each child. On average, our classrooms have a ratio of 10 students per teacher.",
    open: false,
  },
   {
    question: " Are meals provided at the school?",
    answer:
      "Yes, we provide healthy, balanced meals for all students. Our menu includes fresh produce from our school garden, emphasizing nutritious options that support our students' overall well-being.",
    open: false,
  },
]);

const toggleAccordion = (index) => {
  faqs.value[index].open = !faqs.value[index].open;
};
</script>

<style lang="scss" scoped></style>
