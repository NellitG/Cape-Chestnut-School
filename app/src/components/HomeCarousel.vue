<template>
  <div
    class="grid max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12"
  >
    <div class="mr-auto place-self-center lg:col-span-7">
      <h1
        class="max-w-2xl mb-4 justify-center text-center text-3xl font-semibold md:text-5xl xl:text-6xl"
      >
        Our Environment
      </h1>
      <p
        class="max-w-2xl mb-6 font-light text-gray-950 lg:mb-8 md:text-lg lg:text-xl"
      >
        Cape Chestnut School is nestled in a beautiful, scenic environment that enhances the learning experience for our students.
        Surrounded by lush greenery and vibrant Cape Chestnut trees, the school offers a peaceful and inspiring setting for both study and play.
      </p> 
    </div>
    <div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
      <img
        src="@/assets/images/garden.jpg"
        alt="mockup"
      />
    </div>
  </div>

  <div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
      <img
        src="@/assets/images/garden.jpg"
        alt="mockup"
      />
    </div>

    <div class="hidden lg:mt-10 lg:col-span-5 lg:flex">
      <img
        src="@/assets/images/chestnut.jpg"
        alt="mockup"
      />
    </div>

    <div class="hidden lg:mt-10 lg:col-span-5 lg:flex w-full">
      <img
        src="@/assets/images/trees.jpg"
        alt="mockup"
      />
    </div>
  <div
    class="grid max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12"
  >
    <div class="mr-auto place-self-center lg:col-span-7">
      <!-- <h1
        class="max-w-2xl mb-4 text-3xl font-semibold md:text-5xl xl:text-6xl"
      >
        Our Environment
      </h1> -->
      <p
        class="max-w-7xl mb-6 font-semibold text-center text-gray-950 lg:mb-8 md:text-lg lg:text-xl"
      >
        Cape Chestnut School is nestled in a beautiful, scenic environment that enhances the learning experience for our students.
        Surrounded by lush greenery and vibrant Cape Chestnut trees, the school offers a peaceful and inspiring setting for both study and play.
      </p>
    </div>
    
  </div>
</template>

<!-- <script setup>
import { ref, onMounted, onUnmounted } from "vue";
import tree from "../assets/images/Home/033.jpg"
import bird from "../assets/images/Home/062.jpg"
import mountain from "../assets/images/Home/020.jpg"
import leaf from "../assets/images/Home/fee 245.jpg"

// Carousel items data
const carouselItems = ref([
  {
    image:
    leaf,
    alt: "staff",
  },
  {
    image:
      bird,
    alt: "staff",
  },
  {
    image:
      tree,
    alt: "staff",
  },
  {
    image:
      mountain,
    alt: "staff",
  },
]);

// Duplicate the carousel items to create a seamless loop
const extendedCarouselItems = ref([
  ...carouselItems.value,
  ...carouselItems.value,
]);

// Variables for carousel position and transition
const currentPosition = ref(0);
const isTransitioning = ref(true);
const itemWidth = ref(0); // Width of each carousel item

// Auto-slide logic
let interval;
const slideInterval = 3000;

onMounted(() => {
  // Calculate the width of each carousel item
  itemWidth.value = document.querySelector(".carousel-item").offsetWidth;
  startCarousel();
});

onUnmounted(() => {
  stopCarousel();
});

// Methods to navigate the carousel
const startCarousel = () => {
  interval = setInterval(nextItem, slideInterval);
};

const stopCarousel = () => {
  clearInterval(interval);
};

const nextItem = () => {
  currentPosition.value += itemWidth.value;
  isTransitioning.value = true;
};

const handleTransitionEnd = () => {
  if (currentPosition.value >= itemWidth.value * carouselItems.value.length) {
    currentPosition.value = 0;
    isTransitioning.value = false;
  }
};
</script> -->

<!-- <style scoped>
.carousel-container {
  overflow: hidden;
  width: 100%;
}

.carousel-track {
  display: flex;
  transition: transform 0.5s ease;
}

.carousel-item {
  flex: 0 0 auto;
  width: 100%;
}

.slide-enter-active,
.slide-leave-active {
  transition: transform 0.5s ease;
}

.slide-enter,
.slide-leave-to {
  transform: translateX(100%);
}
</style> -->
