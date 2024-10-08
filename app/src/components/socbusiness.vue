<template>
  <div class="container mx-auto p-4">
    <nav
      class="text-5xl font-bold text-secondary-color leading-loose tracking-wide mt-4"
    >
      <h1>School of Beauty/Cosmetology</h1>
    </nav>

    <div class="flex flex-col md:flex-row justify-center md:gap-8 p-4">
      <div
        class="bg-gray-100 rounded-lg p-4 mb-4 md:mb-0 md:w-1/2 flex flex-col"
      >
        <div class="text-black flex-grow">
          Cosmetology is the study and application of beauty treatments.<br /><br />
          Comprehensive Training: A cosmetology school provides comprehensive
          training in various beauty treatments, including practical and
          theoretical knowledge. <br /><br />
          Licensing and Certification: Graduates often need to pass state or
          national licensing exams to practice professionally. <br /><br />
          Career Opportunities: Cosmetologists can work in salons, spas, beauty
          schools, or as freelance professionals.
        </div>
      </div>
      <div class="md:w-1/2 flex flex-col">
        <img
          src="../assets/images/beauty/pexels-rdne-7697401.avif"
          alt=""
          class="w-full h-full object-cover rounded-lg"
        />
      </div>
    </div>

    <nav
      class="bg-secondary-color py-2 flex flex-row md:flex-row flex-wrap justify-start md:justify-start gap-4 md:gap-8 mt-4 px-5 text-gray-200"
    >
      <a href="#" class="mb-2 md:mb-0">Overview</a>
      <a href="#" class="mb-2 md:mb-0">Syllabus</a>
      <a href="#enrollment" class="mb-2 md:mb-0">Enrollment</a>
      <a href="#faqs" class="mb-2 md:mb-0">FAQs</a>
    </nav>

    <div class="flex flex-col items-center justify-center mt-12">
      <hr class="h-0.5 bg-black w-28" />
      <hr />
      <h3 class="text-gray-600 text-lg">Key Concepts</h3>
      <hr class="h-0.5 bg-black w-28" />
    </div>

    <div class="flex flex-col md:flex-row justify-center gap-8 md:gap-20 mt-12">
      <div class="text-center md:text-left">
        Our mission is to provide top-tier cosmetology education 
        that empowers students to excel as professionals 
        and entrepreneurs in the beauty industry.
      </div>

      <div class="text-center md:text-left">
        We are committed to fostering creativity, confidence, 
        and a passion for beauty while instilling the highest 
        standards of professionalism and ethics.
      </div>
    </div>

    <hr class="h-0.5 bg-black my-3" />

    <section class="py-10 lg:py-20 max-w-7xl mx-auto px-4 sm:px-8">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- card 1 -->
        <div class="w-full relative rounded-2xl overflow-hidden flex flex-col">
          <img
            src="../assets/images/beauty/pexels-shvetsa-5069432.avif"
            alt="Night Lights"
            class="w-full h-2/3 object-cover"
          />
          <div
            class="bg-gray-900 bg-opacity-30 p-6 flex-grow rounded-b-2xl flex flex-col justify-between"
          >
            <div>
              <h1 class="text-2xl font-semibold text-white flex items-center">
                Beauty Therapy
              </h1>
              <p class="text-white py-3">
                Beauty therapy involves treatments that enhance the skin and
                overall appearance, including facials, waxing, and body
                treatments
              </p>
            </div>
          </div>
        </div>

        <!-- card 2 -->
        <div class="w-full relative rounded-2xl overflow-hidden flex flex-col">
          <img
            src="../assets/images/beauty/pexels-barbara-olsen-7879492.avif"
            alt="Night Lights"
            class="w-full h-2/3 object-cover"
          />
          <div
            class="bg-gray-900 bg-opacity-30 p-6 flex-grow rounded-b-2xl flex flex-col justify-between"
          >
            <div>
              <h1 class="text-2xl font-semibold text-white justify-start">
                Hair Dressing
              </h1>
              <p class="text-white py-3">
                Hairdressing involves cutting, coloring, styling, and treating
                hair to enhance a person's appearance.
              </p>
            </div>
          </div>
        </div>
        <!-- card 3 -->
        <div class="w-full relative rounded-2xl overflow-hidden flex flex-col">
          <img
            src="../assets/images/beauty/pexels-cottonbro-3997391.avif"
            alt="Night Lights"
            class="w-full h-2/3 object-cover"
          />
          <div
            class="bg-gray-900 bg-opacity-30 p-6 flex-grow rounded-b-2xl flex flex-col justify-between"
          >
            <div>
              <h1 class="text-2xl font-semibold text-white justify-start">
                Nail Technology
              </h1>
              <p class="text-white py-3">
                Nail technology focuses on the care and decoration of nails,
                including manicures, pedicures, and nail art.
              </p>
            </div>
          </div>
        </div>
        <!-- card 4 -->
        <div class="w-full relative rounded-2xl overflow-hidden flex flex-col">
          <img
            src="../assets/images/beauty/pexels-rdne-7697401.avif"
            alt="Night Lights"
            class="w-full h-2/3 object-cover"
          />
          <div
            class="bg-gray-900 bg-opacity-30 p-6 flex-grow rounded-b-2xl flex flex-col justify-between"
          >
            <div>
              <h1 class="text-2xl font-semibold text-white justify-start">
                Barbering
              </h1>
              <p class="text-white py-3">
                <span class="font-bold">Definition:</span> Barbering specializes
                in cutting, grooming, and styling men's hair and facial hair.
              </p>
            </div>
          </div>
        </div>
        <!-- card 5 -->
        <div class="w-full relative rounded-2xl overflow-hidden flex flex-col">
          <img
            src="../assets/images/beauty/pexels-enginakyurt-5378219.avif"
            alt="Night Lights"
            class="w-full h-2/3 object-cover"
          />
          <div
            class="bg-gray-900 bg-opacity-30 p-6 flex-grow rounded-b-2xl flex flex-col justify-between"
          >
            <div>
              <h1 class="text-2xl font-semibold text-white justify-start">
                Hot Stone Massage
              </h1>
              <p class="text-white py-3">
                A hot stone massage is a type of massage therapy that involves
                using heated stones to relax and ease tense muscles.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Fees Table -->
    <section class="max-w-7xl mx-auto">
      <div>
        <h1 class="text-secondary-color text-3xl font-bold mb-8 text-center">
          Fees Structure
        </h1>
      </div>
      <div class="overflow-x-auto">
        <table
          class="shadow-lg bg-white border-collapse mx-auto w-full text-lg"
        >
          <tr>
            <th class="bg-gray-300 border text-left px-8 py-4">Course Name</th>
            <th class="bg-gray-300 border text-left px-8 py-4">
              Minimum Requirements
            </th>
            <th class="bg-gray-300 border text-left px-8 py-4">Tution Fee</th>
          </tr>
          <tr class="hover:bg-gray-100">
            <td class="border px-8 py-4">Beauty therapy</td>
            <td class="border px-8 py-4">KCPE/ KCSE Certificate</td>
            <td class="border px-8 py-4">15,000</td>
          </tr>
          <tr class="hover:bg-gray-100">
            <td class="border px-8 py-4">Hair dressing</td>
            <td class="border px-8 py-4">KCPE/ KCSE Certificate</td>
            <td class="border px-8 py-4">15,000</td>
          </tr>
          <tr class="hover:bg-gray-100">
            <td class="border px-8 py-4">Nail Technology</td>
            <td class="border px-8 py-4">KCPE/ KCSE Certificate</td>
            <td class="border px-8 py-4">15,000</td>
          </tr>
          <tr class="hover:bg-gray-100">
            <td class="border px-8 py-4">Barbering</td>
            <td class="border px-8 py-4">KCPE/ KCSE Certificate</td>
            <td class="border px-8 py-4">15,000</td>
          </tr>
          <tr class="hover:bg-gray-100">
            <td class="border px-8 py-4">Hot Stone Massage</td>
            <td class="border px-8 py-4">KCPE/ KCSE Certificate</td>
            <td class="border px-8 py-4">15,000</td>
          </tr>
        </table>
      </div>
    </section>
  </div>
</template>
