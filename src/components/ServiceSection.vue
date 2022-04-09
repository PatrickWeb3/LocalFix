<template>
  <div class="serviceSection bg-center bg-cover relative">
    <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 lg:top-1/4 lg:left-1/2 transform lg:-translate-x-1/2 lg:-translate-y-1/2">
      <!-- Upper Text -->
    <div class="">
      <h1 class="text-3xl lg:text-4xl uppercase my-8 lg:my-10 md:w-max md:mx-auto">
        <span class="block md:inline-block md:mr-2 text-gray-900">Expect pure </span>
        <span class="block md:inline-block text-red-700 font-bold">excellence</span>
      </h1>
    </div>
    <!-- Skills Section -->
    <div class="flex flex-col lg:flex-row gap-y-3 lg:gap-x-10 mb-10">
      <!--  -->
      <div class="bg-black w-96 lg:h-72 lg:w-72 mx-auto p-4">
        <div class="bg-gray-800 w-12 h-12 mx-auto rounded-full relative lg:my-4 mb-4">
          <i class="text-gray-200 text-2xl fa-solid fa-user-shield absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2"></i>
        </div>
        <h2 class="text-gray-100 text-2xl font-bold mb-3 border-b border-gray-100 w-2/3 mx-auto pb-3">Top Safety</h2>
        <p class="text-gray-200">We proceed with extreme caution during our services. You are in professional hands and we work at the highest level.</p>
      </div>

      <div class="bg-black w-96 lg:h-72 lg:w-72 mx-auto p-4">
        <div class="bg-gray-800 w-12 h-12 mx-auto rounded-full relative lg:my-4 mb-4">
          <i class="text-gray-200 text-3xl fa-solid fa-award absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2"></i>
        </div>
        <h2 class="text-gray-100 text-2xl font-bold mb-3 border-b border-gray-100 w-2/3 mx-auto pb-3">Smart Choice</h2>
        <p class="text-gray-200">Professionals recommend us, we are the definition of excellence. Top Choice in Chicago by specialists. Schedule with us.</p>
      </div>

      <div class="bg-black w-96 lg:h-72 lg:w-72 mx-auto p-4">
        <div class="bg-gray-800 w-12 h-12 mx-auto rounded-full relative lg:my-4 mb-4">
          <i class="text-gray-200 text-3xl fa-solid fa-wrench absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2"></i>
        </div>
        <h2 class="text-gray-100 text-2xl font-bold mb-3 border-b border-gray-100 w-2/3 mx-auto pb-3">Best Service</h2>
        <p class="text-gray-200">We proceed with passion when working, we assure that we only provide excellence. We are highly recommended.</p>
      </div>
    </div>
    </div>
  </div>
</template>

<style>

  .serviceSection {
    background-image: url("/src/static/ServiceBg.jpg");
    height:95vh;
  }

</style>