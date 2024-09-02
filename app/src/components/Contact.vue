<template>
 <section class="gradient-form h-full bg-neutral-200 dark:bg-neutral-700 ">
    <div class="container h-full p-10 ">
      <div
        class="flex h-full flex-wrap items-center justify-center text-neutral-800 dark:text-neutral-200">
        <div class="w-full">
          <div
            class="block rounded-lg bg-white shadow-lg dark:bg-neutral-800">
            <div class="g-0 lg:flex lg:flex-wrap">
              <!-- Left column container-->
              <div class="px-4 md:px-0 lg:w-6/12">
                <div class="md:mx-6 md:p-12">
                  <!--Logo-->
                  <div class="text-center">
                    <img
                      class="mx-auto w-48"
                      src="@/assets/images/cape chestnut.jpg.png"
                      alt="logo" />
                    <h4 class="mb-12 mt-10 pb-1 text-3xl font-semibold">
                      Register Today
                    </h4>
                  </div>
  
                  <form>
                    <!-- <p class="mb-4 font-semibold">Please register an account</p> -->
                    <!--Username input-->
                    <div class="relative mb-8 " data-twe-input-wrapper-init>
                      <input
                        type="text"
                        class="peer block min-h-[auto] w-full rounded border-2 border-black bg-transparent px-3 py-[0.32rem] leading-[1.6] outline-none transition-all duration-200 ease-linear focus:placeholder:opacity-100 peer-focus:text-primary data-[twe-input-state-active]:placeholder:opacity-100 motion-reduce:transition-none dark:text-white dark:placeholder:text-neutral-300 dark:autofill:shadow-autofill dark:peer-focus:text-primary [&:not([data-twe-input-placeholder-active])]:placeholder:opacity-0"
                        id="exampleFormControlInput1"
                        placeholder="Username" />
                      <label
                        for="exampleFormControlInput1"
                        class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[1.6] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[0.9rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[twe-input-state-active]:-translate-y-[0.9rem] peer-data-[twe-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-400 dark:peer-focus:text-primary"
                        >Email address
                      </label>
                    </div>
  
                    <!--Password input-->
                    <div class="relative mb-4" data-twe-input-wrapper-init>
                      <input
                        type="password"
                        class="peer block min-h-[auto] w-full rounded border-2 borderblack bg-transparent px-3 py-[0.32rem] leading-[1.6] outline-none transition-all duration-200 ease-linear focus:placeholder:opacity-100 peer-focus:text-primary data-[twe-input-state-active]:placeholder:opacity-100 motion-reduce:transition-none dark:text-white dark:placeholder:text-neutral-300 dark:autofill:shadow-autofill dark:peer-focus:text-primary [&:not([data-twe-input-placeholder-active])]:placeholder:opacity-0"
                        id="exampleFormControlInput11"
                        placeholder="Password" />
                      <label
                        for="exampleFormControlInput11"
                        class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[1.6] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[0.9rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[twe-input-state-active]:-translate-y-[0.9rem] peer-data-[twe-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-400 dark:peer-focus:text-primary"
                        >Password
                      </label>
                    </div>
  
                    <!--Submit button-->
                    <div class="mb-12 pb-1 pt-1 text-center">
                      <button
                        class="mb-3 inline-block w-full rounded px-6 pb-2 pt-2.5 text-xs font-medium uppercase leading-normal text-white shadow-dark-3 transition duration-150 ease-in-out hover:shadow-dark-2 focus:shadow-dark-2 focus:outline-none focus:ring-0 active:shadow-dark-2 dark:shadow-black/30 dark:hover:shadow-dark-strong dark:focus:shadow-dark-strong dark:active:shadow-dark-strong"
                        type="button"
                        data-twe-ripple-init
                        data-twe-ripple-color="light"
                        style="
                          background: linear-gradient(to right, #b44593, #b44593, #b44593, #a7f3d0);
                        ">
                        Sign up
                      </button>
  
                      <!--Forgot password link-->
                      <a href="#!">Terms and conditions</a>
                    </div>
  
                    <!--Register button-->
                    <div class="flex items-center justify-between pb-6">
                      <p class="mb-0 me-2">Have an account?</p>
                      <button
                        type="button"
                        class="inline-block rounded border-2 border-danger px-6 pb-[6px] pt-2 text-xs font-medium uppercase leading-normal text-danger transition duration-150 ease-in-out hover:border-danger-600 hover:bg-danger-50/50 hover:text-danger-600 focus:border-danger-600 focus:bg-danger-50/50 focus:text-danger-600 focus:outline-none focus:ring-0 active:border-danger-700 active:text-danger-700 dark:hover:bg-rose-950 dark:focus:bg-rose-950"
                        data-twe-ripple-init
                        data-twe-ripple-color="light">
                        Login
                      </button>
                    </div>
                    
                  </form>
                </div>
              </div>
  
              <!-- Right column container with background and description-->
              <div
                class="flex items-center rounded-b-lg lg:w-6/12 lg:rounded-e-lg lg:rounded-bl-none"
                style="background: linear-gradient(to right, #b44593, #b44593, #b44593, #a7f3d0)">
                <div class="px-4 py-6 text-white md:mx-6 md:p-12">
                  <h4 class="mb-6 text-xl font-semibold">
                    We are more than just a company
                  </h4>
                  <p class="text-lg text-gray-950">
                    Cape Chestnut School<br><br>
                Address:<br>
                Merisho ,<br>
                Along the new Forest Rd<br><br>

                Phone:<br>
                +254722883181<br>
                +254726082996<br><br>

                Email:<br>
                capechestnutschool@gmail.com<br><br>

                Website:<br>
                www.capechestnutschool.org<br><br>

                Office Hours:<br>
                Monday to Friday: 8:00 AM - 4:00 PM<br><br>

                Social Media:<br>

                Facebook: facebook.com/capechestnutschool<br>
                Twitter: twitter.com/CapeChestnutSch<br>
                Instagram: instagram.com/capechestnutschool<br>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>
