<template>
  <div class="font-sans text-gray-900">  

    <!-- Section 1: What makes us different -->
    <section class="py-16 bg-white text-center px-6 md:px-12 lg:px-20">
      <h2 class="text-2xl md:text-3xl font-bold mb-10 text-[#161723]">
        What makes us different <br />
        <span class="font-bold">makes them stronger</span>
      </h2>

      <div class="flex flex-col md:flex-row justify-center items-center gap-12">
        <!-- Left features -->
        <div class="flex flex-col gap-6 text-left">
          <div class="flex items-start gap-3">
            <img src="../assets/food1.png" class="w-12 h-12 mt-1" />
            <div>
              <h3 class="font-semibold">Real Food</h3>
              <p class="text-sm text-gray-600">Wholesome recipes for dogs with real meat and veggies.</p>
            </div>
          </div>

          <div class="flex items-start gap-3">
            <img src="../assets/pet-bowl 1.png" class="w-12 h-12 mt-1" />
            <div>
              <h3 class="font-semibold">Premium Ingredient</h3>
              <p class="text-sm text-gray-600">Elevating pet care with unmatched safety and quality.</p>
            </div>
          </div>
        </div>

        <!-- Center image -->
        <div>
          <img src="../assets/Frame 1171276495.png" alt="dog food" class="w-64 rounded-full shadow-md" />
        </div>

        <!-- Right features -->
        <div class="flex flex-col gap-6 text-left">
          <div class="flex items-start gap-3">
            <img src="../assets//pet-food 1.png" class="w-12 h-12 mt-1" />
            <div>
              <h3 class="font-semibold">Made Fresh</h3>
              <p class="text-sm text-gray-600">We prioritize maintaining the integrity of whole foods and nutrition.</p>
            </div>
          </div>

          <div class="flex items-start gap-3">
            <img src="../assets/vet 1.png" class="w-12 h-12 mt-1" />
            <div>
              <h3 class="font-semibold">Vet Developed</h3>
              <p class="text-sm text-gray-600">We raise the bar for dog nutrition, surpassing industry expectations.</p>
            </div>
          </div>
        </div>
      </div>

        <!-- CTA Button -->
        <div class="mt-12">
          <button class="mx-6 bg-[#EE6F4B] hover:bg-[#EE6F4B]  text-white font-semibold px-8 md:px-16 py-2 rounded-lg text-lg transition-colors">
            Get your dog's healthy meal today!
          </button>
          
          <!-- Payment icons -->
          <div class="flex flex-col md:flex-row items-center justify-center md:space-x-4 space-y-2 md:space-y-0 mt-4 text-sm text-gray-500">
            <span class="flex items-center">
              <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M5.33801 1.59C4.38559 1.85248 3.43965 2.1379 2.50101 2.446C2.41529 2.47376 2.3391 2.52504 2.28111 2.59399C2.22312 2.66295 2.18567 2.7468 2.17301 2.836C1.61901 6.993 2.89901 10.026 4.42601 12.024C5.07252 12.8784 5.84341 13.6311 6.71301 14.257C7.05901 14.501 7.36501 14.677 7.60601 14.79C7.72601 14.847 7.82401 14.885 7.89901 14.908C7.93181 14.9195 7.96562 14.9279 8.00001 14.933C8.03398 14.9275 8.06743 14.9191 8.10001 14.908C8.17601 14.885 8.27401 14.847 8.39401 14.79C8.63401 14.677 8.94101 14.5 9.28701 14.257C10.1566 13.6311 10.9275 12.8784 11.574 12.024C13.101 10.027 14.381 6.993 13.827 2.836C13.8145 2.74676 13.777 2.66285 13.719 2.59388C13.661 2.52491 13.5848 2.47366 13.499 2.446C12.848 2.233 11.749 1.886 10.662 1.591C9.55201 1.29 8.53101 1.067 8.00001 1.067C7.47001 1.067 6.44801 1.29 5.33801 1.591V1.59ZM5.07201 0.56C6.15701 0.265 7.31001 0 8.00001 0C8.69001 0 9.84301 0.265 10.928 0.56C12.038 0.86 13.157 1.215 13.815 1.43C14.0901 1.52085 14.334 1.68747 14.5187 1.9107C14.7034 2.13394 14.8213 2.40474 14.859 2.692C15.455 7.169 14.072 10.487 12.394 12.682C11.6824 13.621 10.834 14.4479 9.87701 15.135C9.5461 15.3728 9.19549 15.5819 8.82901 15.76C8.54901 15.892 8.24801 16 8.00001 16C7.75201 16 7.45201 15.892 7.17101 15.76C6.80452 15.5819 6.45391 15.3728 6.12301 15.135C5.16603 14.4478 4.31759 13.621 3.60601 12.682C1.92801 10.487 0.545005 7.169 1.14101 2.692C1.17869 2.40474 1.29665 2.13394 1.48132 1.9107C1.666 1.68747 1.9099 1.52085 2.18501 1.43C3.1402 1.11681 4.10281 0.826725 5.07201 0.56Z" fill="#424153"/>
              <path d="M10.8546 5.14687C10.9012 5.19331 10.9381 5.24849 10.9633 5.30923C10.9885 5.36998 11.0015 5.4351 11.0015 5.50087C11.0015 5.56663 10.9885 5.63175 10.9633 5.6925C10.9381 5.75324 10.9012 5.80842 10.8546 5.85487L7.85461 8.85487C7.80817 8.90143 7.75299 8.93837 7.69225 8.96358C7.6315 8.98878 7.56638 9.00176 7.50061 9.00176C7.43484 9.00176 7.36972 8.98878 7.30898 8.96358C7.24823 8.93837 7.19306 8.90143 7.14661 8.85487L5.64661 7.35487C5.60012 7.30838 5.56325 7.25319 5.53809 7.19245C5.51293 7.13171 5.49998 7.06661 5.49998 7.00087C5.49998 6.93512 5.51293 6.87002 5.53809 6.80928C5.56325 6.74854 5.60012 6.69335 5.64661 6.64687C5.6931 6.60038 5.74829 6.5635 5.80903 6.53834C5.86977 6.51318 5.93487 6.50023 6.00061 6.50023C6.06636 6.50023 6.13146 6.51318 6.1922 6.53834C6.25294 6.5635 6.30812 6.60038 6.35461 6.64687L7.50061 7.79387L10.1466 5.14687C10.1931 5.1003 10.2482 5.06336 10.309 5.03815C10.3697 5.01295 10.4348 4.99997 10.5006 4.99997C10.5664 4.99997 10.6315 5.01295 10.6922 5.03815C10.753 5.06336 10.8082 5.1003 10.8546 5.14687Z" fill="#424153"/>
              </svg>

             <span class="ml-1"> 30-day money back guarantee</span>
            </span>
            <div class="flex space-x-2">
              <img src="../assets/paypal.png" class="w-8 h-5 flex items-center justify-center"/>
              <img src="../assets/visa.png" class="w-8 h-5 flex items-center justify-center"/>
              <img src="../assets/mastercard.png" class="w-8 h-5 flex items-center justify-center"/>
              <img src="../assets/735634bc42390c9bfc06ce4987dcbfa88deeb58a.png" class="w-8 h-5 flex items-center justify-center"/>
              <img src="../assets/af7b049d9ca124b78750b3d1064945eeb315ee6a.png" class="w-8 h-5 flex items-center justify-center"/>
            </div>
          </div>
        </div>
    </section>

    <!-- Section 2: Nutrition foundation -->
    <section class="py-16 bg-gray-50 px-6 md:px-12 lg:px-20">
    <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-stretch">

      <!-- Left text -->
      <div class="flex flex-col justify-center h-full">
        <h2 class="text-2xl md:text-2xl lg:text-3xl font-semibold mb-4 leading-snug">
          Nutrition is the foundation for longer, healthier lives in dogs.
        </h2>

        <p class="text-gray-600 mb-6 text-base md:text-sm lg:text-base">
          Invest in your dog's future with our scientifically formulated
          superfood-powered supplements. Give them the nutrition they
          deserve and watch them thrive with vitality, energy, and the joy
          of a longer, healthier life.
        </p>

        <ul class="mb-6 text-gray-700 space-y-3 text-base md:text-sm lg:text-base">
          <span class="font-semibold block mb-4 text-[#161723]">Key Points:</span>

          <li class="flex items-start border-b border-gray-300 pb-3">
            <span class="text-[#EE6F4B] font-bold w-24 text-2xl">97%</span>
            <p class="flex-1">
              Dogs choose our dog food over leading brands because of its
              real functional ingredients and delicious flavor.
            </p>
          </li>

          <li class="flex items-start border-b border-gray-300 pb-3">
            <span class="text-[#EE6F4B] font-bold w-24 text-2xl">84%</span>
            <p class="flex-1">
              Our dog food provides superior nutrition and a patented
              probiotic for optimal nutrient absorption.
            </p>
          </li>

          <li class="flex items-start pb-3">
            <span class="text-[#EE6F4B] font-bold w-24 text-2xl">92%</span>
            <p class="flex-1">
              Our dog food's high protein and fat digestibility contribute
              to ideal stool quality.
            </p>
          </li>
        </ul>

        <button
          class="bg-[#EE6F4B] text-white px-6 py-3 rounded-md hover:bg-[#EE6F4B] transition text-sm md:text-xs lg:text-sm">
          Give your furry friend the gift of wholesome nutrition
        </button>
      </div>

      <!-- Right image -->
      <div class="flex items-center justify-center h-full">
        <img
          src="../assets/6136b8cbaf00668ccc9824e4a89f2de6355161fb.png"
          alt="dog with food"
          class="rounded-lg shadow-md object-cover h-full w-full max-h-[450px]" />
      </div>

    </div>
    </section> 

    <!-- Section 3: Gastrointestinal health --> 
    <section class="py-16 bg-white px-6 md:px-12 lg:px-20">
      <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
        <!-- Left image -->
        <div>
          <img src="../assets/9a4409f684a5519dabc916a48f3dd3616198aa78.gif" alt="dogs eating" class="rounded-lg shadow-md" />
        </div>

        <!-- Right text -->
        <div>
          <h2 class="text-2xl md:text-3xl font-semibold mb-4">
            Improve overall gastrointestinal health for better nutrient absorption
          </h2>
          <p class="text-gray-600">
            Through rigorous scientific studies and consultations with veterinarians, we have created a breakthrough formula exclusively tailored to combat the health challenges prevalent in dogs. A staggering 91% of our customers have reported significant improvements in their dogs' health after incorporating our product into their diet.
          </p>
        </div>
      </div>
    </section> 

    <!-- Section 4: Prebiotics --> 
    <section class="py-12 px-6 md:px-12 lg:px-20">
      <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
        <!-- Left text -->
        <div>
          <h2 class="text-2xl md:text-3xl font-semibold mb-4">
            Prebiotics nourish the beneficial gut bacteria, supporting digestive health
          </h2>
          <p class="text-gray-600">
            Our dog food formula contains carefully selected prebiotics that work in harmony with the gut microbiota, providing the necessary nutrients for the growth and maintenance of beneficial bacteria, ultimately supporting digestive health.
          </p>
        </div>

        <!-- Right image -->
        <div>
          <img src="../assets/29e727e2150c8fca8f87c017fe9ac37b42bfc610.jpg" alt="dog food" class="rounded-lg shadow-md" />
        </div>
      </div>
    </section> 

  </div>
</template>


