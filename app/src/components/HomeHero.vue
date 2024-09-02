<template>
  <div class="py-0">
    <div class="!flex h-[90vh] w-full items-center justify-between px-0">
      <img
        src="../assets/images/Home/fee 237.jpg"
        alt="bg-img"
        class="absolute inset-0 ml-auto h-full lg:rounded-bl-[100px] object-cover object-center"
      />
      <div class="container mx-auto lg:mt-0">
        <img
                      class="mx-auto w-48"
                      src="@/assets/images/cape chestnut.jpg.png"
                      alt="logo" />
        <div class="grid grid-cols-12 text-start lg:text-start">
          <div
            class="relative flex flex-col bg-clip-border lg:ml-20 text-gray-700 px-16 py-10 border border-white shadow-lg col-span-full rounded-xl bg-transparent shadow-black/10 backdrop-blur-sm backdrop-saturate-200 xl:col-span-8 mt-28"
          >
            <h1
              class="tracking-normal font-semibold text-white text-5xl !leading-snug lg:text-6xl"
            >
              Cape Chestnut School
            </h1>
            <p
              class="antialiased font-sans text-2xl font-semibold leading-relaxed text-inherit mb-10 mt-6 text-white"
            >
               Good Education, Good Character
            </p>
            <div class="flex justify-center gap-4 mb-8 lg:justify-start">
              <router-link to="/contact">
              <button
                class="align-middle select-none font-sans font-semibold text-center uppercase transition-all disabled:opacity-50 disabled:shadow-none disabled:pointer-events-none text-xs py-3 px-6 rounded-lg hover:bg-green-500 text-white border-2 border-green-500 shadow-md shadow-primary-color/10 hover:shadow-lg hover:shadow-primary-color/10 focus:opacity-[0.85] focus:shadow-none active:opacity-[0.85] active:shadow-none"
                type="button"
              >
                contact us
                </button>
              </router-link>
              <router-link to="/academics">
                <button
                class="align-middle select-none font-semibold text-center uppercase transition-all disabled:opacity-50 disabled:shadow-none disabled:pointer-events-none text-xs py-3 px-6 rounded-lg border-green-500 border-2 hover:bg-green-500 text-white hover:opacity-75 focus:ring focus:ring-gray-300 active:opacity-[0.85]"
                type="button"
              >
                read more
              </button>
            </router-link>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- <div class="grid grid-cols-2 sm:grid-cols-4 justify-items-center place-items-center gap-5 sm:gap-0">
      <div class="flex gap-1">
        <p class="skew-x-12 h-24 w-4 bg-primary-color rounded-l-md"></p>
        <button
          class="skew-x-12 h-24 w-48 bg-secondary-color text-white font-bold text-2xl rounded-r-md tracking-wide"
        >
          Courses
        </button>
        
      </div>
      <div class="flex gap-1">
        <p class="skew-x-12 h-24 w-4 bg-primary-color rounded-l-md"></p>
        <button
          class="skew-x-12 h-24 w-48 bg-secondary-color  text-white font-bold text-2xl rounded-r-md tracking-wide"
        >
          About
        </button>
        
      </div>
      <div class="flex gap-1">
        <button
          class="skew-x-12 h-24 w-48 bg-secondary-color text-white font-bold text-2xl rounded-l-md tracking-wide"
        >
          Campus Life
        </button>
        <p class="skew-x-12 h-24 w-4 bg-primary-color rounded-r-md"></p>
      </div>
      <div class="flex gap-1">
        <button
          class="skew-x-12 h-24 w-48 bg-secondary-color text-white font-bold text-2xl rounded-l-md tracking-wide"
        >
          Apply Today
        </button>
        <p class="skew-x-12 h-24 w-4 bg-primary-color rounded-r-md"></p>
      </div>
    </div> -->
  </div>
</template>

<script></script>

<style lang="scss" scoped></style>
